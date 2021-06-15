# ngx_http_srcache_filter_module

Transparent subrequest-based caching layout for arbitrary nginx locations.

- Official: https://github.com/openresty/srcache-nginx-module
- Build: https://github.com/nginx-with-docker/srcache-nginx-module-src
## Nginx Images

<table>
    <thead>
        <tr>
            <th>Nginx Version</th>
            <th>Module Version</th>
            <th>Docker Images</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.21.0</td>
            <td>master (2020.10)</td>
            <td><ul>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-srcache-master</li>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-srcache-master-alpine</li>
            </ul></td>
        </tr>
        <tr>
            <td>1.21.0</td>
            <td>0.32 (2020.07)</td>
            <td><ul>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-srcache-0.32</li>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-srcache-0.32-alpine</li>
            </ul></td>
        </tr>
    </tbody>
</table>

## TODO

- try merge changes: https://github.com/openresty/srcache-nginx-module/pulls
