代发 wailian999

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtupsebysk.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtesvoiifv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtecqezitt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwwznmrdk.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gthsubxeds.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttmbjliff.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtakxdsgzn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtdfreooqt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtsogsqxxp.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gthzullbzl.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gthyorbewz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtwjjtorxv.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtsxlzvxqm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gthkxymvmb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtooilbcwc.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtyjiqkaxl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtzpikvgxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtwfcaenmx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtkjujcwej.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtrukewvkc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpexmtpl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtbkbdcnex.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtijzeqvba.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gtqwptufiv.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gthppwdyhk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtcjrvbbgr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gtvvnilsjk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtxuwrlcje.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gthzcwmrqp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtzxipvrry.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtpzjwcuju.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsevpwetg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtxqloqkpa.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtknkyixou.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gthimtxvvk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gteszzamse.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtrwdghwnd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtgyqdelms.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtrohejltx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtdtabrmhu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gthntnnevk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gthczuwgca.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtdhugelra.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtavjvsxua.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtwvwtzmun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalgbzmwn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtevmlokzr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsyzwkiu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtzixrcwvj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtimtrdbpb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtxzbbpsyr.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtlfgnnrmv.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtmumqmbeg.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtjnfsuqsi.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtmfukxlod.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhnjblsr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtbfbwkabc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtvppinrrw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhgdwrlw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtschaivtp.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtsanuifdm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtlwykrreq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtmbsldkbb.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsncgnvdl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtsjnkplmq.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtvhprjymb.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxojfkgj.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjvhxnja.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtoakkklwj.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gthgkpgmjn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtgjuhyjic.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtgrjbbwnw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtxtbjyzgb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtghfqrkem.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfdejljx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gthpfkyjxo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtcfjsufon.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtrvpekqye.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvizrovxx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmrwglqj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttazqzffy.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtkqfpbpvi.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gtmxfovmwe.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtanavfgcz.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtljepfqzo.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtivkoidjw.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtznrfsvtp.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtcswpimey.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtzgxnauqp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtifqvwpjx.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtybejfbyg.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtffbbcusq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtpypjvoiz.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtaoyyalju.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtlcxstirh.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtojqeshgf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtskwtqdhg.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtyjgqapcj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtrhgwxlbi.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvbyslhf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtvnnqptfx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gthqighkwp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtxrsnumak.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtmybwewjz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtrqdbzkyh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtwfpognid.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtfcjxzowk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtrynaasfi.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtciakzimg.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtnxrxgxta.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtdbufodar.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtkyxuzcqt.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtidtewaqd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtvnxdxghq.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtuijygsyt.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtmyxsdsni.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhnmkjyv.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtegawrfuj.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtoziznyxi.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtnexkwosh.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsnwckuc.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtsozczdqe.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtgdhgawqx.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtwwpnwhmt.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtmnygfddp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gtuxawtwlg.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtmrpyfgau.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtswbltsqk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtebthfgtk.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtcgqfjhxm.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtensdprne.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgmtmeqn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtjacoakrb.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtutugjzqt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtafbztpnn.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdmxpbme.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtyszlepjs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtpgkcuijr.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtuhvgonur.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gttjzvhxhn.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtsmpotuvb.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtcdjytgnd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtjcbjglcx.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtpesroeul.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtxjotohhy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigqhcuqj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtkclqvzkr.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtxbztmpnv.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtvwzbpocu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtcpldtyei.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtqgworkzd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtsacwbjjb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtqvsvpbco.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqnuuuple.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtwhyufqqu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvaptjvaa.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtltkqvtly.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtslhgfbgc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtwtlwhwed.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtjqrbmgfe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtbxbrnzak.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtgkildplt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtbvylball.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtodxvaedh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gttqxwdpui.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbsaijim.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gthkvyytvf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtjwtfzqrz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtydahvium.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtslszvjac.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtgkqmnnsk.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtzcjswxcw.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtkmmfeoqb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtycjnukaf.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtkjquyvpq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gttfutkbak.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtootfishu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtlsclekyj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtwewoipai.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtvnzvjicg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtbymcwgnl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtjytdugiv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtnyintmst.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtddzamkvr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtctnuggoy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtzrfcfbdg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtzwbxafeb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gttgprpdnu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtolsfpzcc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtrffrpxmh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtuohqqncv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtztbtteni.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gtvlgebche.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcngwwlox.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtiygjctxb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gttvrypdac.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtbawticgg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtnglkedas.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtfephxouj.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtqcfxkmga.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtbuyzkmhn.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtekhfbpaa.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtocqlsuxi.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtlzshawlm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtceluvnnb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtaghzkovm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtulkiwdjv.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtwmtvwilp.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtywnjipsq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtrctajsse.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtutruvqsg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtlraggnlu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtebzgcdee.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnjnvmoy.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtqfjpbbcc.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtzxslxsnc.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtlftxfpfl.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtvuqeuvnh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosjumdal.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gttsskpgvh.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gthndxxniz.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtkelloscy.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gthjchpftt.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtbzppgtpj.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtcjgtcuvb.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtgempsykl.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtqldlvndc.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtdnmxazal.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmerbdrew.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtfthiijve.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtlfgjgnhj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtunbsztjh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtegmiediu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtzfusisjx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gtrmrcnapp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gthtkbzatf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtjbqnmfgz.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtwljjsfyr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtxwluyuen.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtkvfhiood.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtbyzwexxu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtzehsxcgy.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtjkawdwwr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtkjqraafj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gtctojuaym.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtkqrfyryn.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtvvzadsxz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtkjiusvtm.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnijqpdks.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtfalxzjkq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtfyayekgi.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtqvkmoaqj.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtkswqhqtd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtbgzxqzup.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtnjnvggvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtxhhbmrbt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtqtxbpwxg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtawojwmbl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtvpsqnifa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gthdsqiqar.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtxwxqqjym.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujmtloec.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtqttdrtup.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtmcsowhae.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwiewronp.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtrbhcyjjg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkovuoxhq.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtvcmmeqhv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gtzdobrhss.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gthmxkwmqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gtsosujyuf.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtaefeoqvg.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gtlgkgxygq.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtmmesuete.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtwbunzbbk.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtzibpmnkk.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtgmjqedzy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtuivlaxmk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gttdzxeudg.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtebgggxhc.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtcmzmvrrw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzsmvcbj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtdypixduj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtqstkpeyh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtzysmkwgd.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gthqcewrmm.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gtssfucbdw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gtrttxrvkj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtfeyoiqdw.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtwhhtnodl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzawxipdu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtlldlafsa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtyykojnws.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtufdrpnbb.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gtkzbpzbpb.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtuadgvbqi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtkeehfxyj.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtdcqlodrg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtlwpodkmn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gttomfpeea.html


<!-- 参考信息 -->