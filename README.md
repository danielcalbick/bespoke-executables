<h1 align= center>
    Bespoke Executable Files
</h1>

<!-- Main table for layout -->
<table>
  <tr>
    <!-- Left column for Table of Contents -->
    <td width="30%" valign="top">
        <h2 align= center><strong>Table of Contents</strong></h2>
        <div>
          <ol>
            <li><a href="#prereqs">Prerequisites</a></li>
            <li><a href="#install">Installation</a></li>
            <li><a href="#code">Code</a>
              <ol type="i">
                <li><a href="#spotify_rl">sync_recently_liked_spotify.sh</a></li>
              </ol>
            </li>
          </ol>
        </div>
    </td>
    <!-- Right column for Project Description -->
    <td width="70%" valign="top">
      <h2 align= center><strong>Info</strong></h2>
      <p align= justify>
        This repo contains all the executable files I use on my computer. It is where I place things like source code I run on a schedule, or helper functions that I use to run complicated functions having to do with my personal/local computer. For instance, <strong>sync_recently_liked_spotify.sh</strong> is a shell script that envokes a python evironment to connect to spotify and programmatically update my 100 newest liked songs. I can either call that shell script from the command line or create a cron-job that will do it on a set schedule."
      </p>
      <br>
    </td>
  </tr>
</table>

<!-- Additional Sections here -->

<h3 style="your-style-here" id="prereqs">Prerequisites</h3>

<div>
  Well this repo is mostly just for me so there may be some dependencies for the systme that I am using. For example, much like Justin Long, I'm a mac guy; so, much of this is probably written to opperate on a UNIX based OS, and even more specifically probably a mac. However, I'm sure if you find some code interesting you can port the logic and switch it to PC.
</div>

<h3 style="your-style-here" id="install">Installation</h3>

<div>

1. Clone the repo
   <code>git clone https://github.com/danielcalbick/bespoke-executables.git</code>

</div>


<h3 style="your-style-here" id="code">Code:</h3>

<h5 style="your-style-here" id="spotify_rl">sync_recently_liked_spotify.sh</h5>

>This is shell script that envokes a python evironment to connect to spotify and programmatically update my 100 newest liked songs. I can either call that shell script from the command line or create a cron-job that will do it on a set schedule. If you want to use it you need to input your user id for spotify which you can get on [their developer website](https://developer.spotify.com/documentation/web-api){:target="_blank" rel="noopener"}.
