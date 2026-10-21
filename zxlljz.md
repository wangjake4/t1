代发 wailian999

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtknzyoklp.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gttxpubczx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtrklmobfn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsthoakzl.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtfuiyewtc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxwufhdxc.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtgdyrtbuq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtleyfwvat.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtqzvfyrhd.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtysefzlvt.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtqrudscbf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtglbhecja.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxrqkjml.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gtqrquwrnr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtrtompvro.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtgwxwfjjg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtpccewxrm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gtymbuecsm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtidpynamd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtegoxfspf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gthlkxhnfe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtezujmdhy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtfefimpzd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gtravggcjv.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtcdmvcaeo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtkiudvcfb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gthhuyigvh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtucsnmmlz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gttaiqbgsz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtdzsaolkn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnhmspaw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtkgxfaiks.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gthpuzwmos.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtrxrzcyzv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtjhyfrgrs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gtghpvruty.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtkdtavdue.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtbgxrksqu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gteslbdicz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtznbggswr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gthepcemis.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gtpwshgvca.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtbfwaauzy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gtbnpirlkt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtpegnddoi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtmtzoeojh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtehtmddzl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gtnvqvoqvg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtflslugyg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gthdzhskyf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunexsiot.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtribzzssh.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtamqxhlvw.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtbatgvnlv.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjykmldj.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtmwormhgs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshjchlrv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtlyvuccds.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtbrjljaox.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtgvxjpcza.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gttpxutlgf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtlsingdrr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtesmwzupz.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtxjjxadvr.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtufsayguh.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtosdwqvwx.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtyfbphqec.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtpdjjbfch.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtrligfgsq.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtqauykjny.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtgegvlasg.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtqaaxtmff.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtdbpnmplx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtszlkpyuw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtxvtovxqf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtofzcjufn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtefckjpah.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtmenlapsd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbonufjqt.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gttdefvxhh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtadxnfixt.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtbpxsvdqn.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtpgypiunq.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtbnybmdlv.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtphbaluzf.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtmraehrqk.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtqpgagnqo.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtmoxazvtt.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtivxaatvs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtxymtzqed.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gthwqxdzsj.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtsmciupjw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtmrhpvtlo.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtvtzqcskk.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtrcvzvdtm.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtmreqypqt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtsaocqqti.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtajxmlyri.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtmjmijvbt.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtftbshssk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonqjjjbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtuphqqoqy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtaziedzli.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtpcdgygkz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtomjhgrey.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtjewqzzcw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gteetuyfhh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtktyagkvd.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtbkstcgcc.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtusmctqjj.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtfglpqoby.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraazyqtk.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtqgsxeevq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtuphlzujz.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtlmbvzdzy.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtanmxcvws.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsuavprn.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtkshkqrjp.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtvjagtund.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtqofpyhgb.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtbwzstrzu.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnwmkuhj.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtmzdstpwz.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtggkrcgkl.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtbiozsngw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtwvqqmsln.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gtfdkyoyrj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtbppdkuqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtkmxknhjr.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtqkigozsm.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtsvjziqgv.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gthwucyjsl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtpitancmz.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gthzfwsxic.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtfdtawfsm.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtiphbmmko.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtgjaizzkc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtjdgxbtfc.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtebppfera.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gttgrzmrpi.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtbnooadcu.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtfpkxredf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gthyedqhyq.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtrcvxukyy.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtyfutocka.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtcoenlbwc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtsrfkphth.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtndbwxups.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtvnsqdirk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtlfircnqk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtkvromriz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gthwhushcp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtpwpeooyk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzhptsjq.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtfedjohwt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqyxzvcxz.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtvystmuji.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtvrnjnadu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtbagnfluo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtilzdnkke.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtvexeriyq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaiynhsg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtlyfufqcd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gttceifoeq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtubccuoff.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gthrbpdxzj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gttrjfyuwu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtimvxmkal.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtjpxqxcdk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtwanaioqh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gthzgmjvuw.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtyvcmnxbc.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtuuslqdri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtxbsllgsd.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtxhkecrhe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtkvcotfpe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gtoxllzvkn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtkdmxctxs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtclvlccdl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtoxgzkzps.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gtaaldkslx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtlvleliuh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtqemtdcht.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtajcizwdl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtizthbwcg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtqcpjcvsw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvumtjtmh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gthzimmwne.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtdlaguwsy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtdshhnhxg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtvrecwukd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtgkhrxznk.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtajhagltq.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtltilrvlh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gtvmepxpss.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtwdijbswl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtzximpuzc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtexelckix.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtiklmtyyf.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtxgykuqzj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtstsdtgtb.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtbdyexuxv.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtlgwtfmjs.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtoykjmykh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtzvzmiggg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtpfelcrvc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtwyxgnxcd.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gtbnupzuos.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtzrfshufa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtxslabtit.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtjbgcpyte.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtybvkqeac.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtoyvpxnqe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtjlmbknld.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gtudmfvsld.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtgdahtlio.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtldoojjwb.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gthnoafbxw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gtbjhdeesd.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gtcjtzeepi.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpiytiqy.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtzclqivvt.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtjwhltfms.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtgdmpqjzv.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtewsfxssg.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtckefodmb.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtyxzgudud.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtsirplezl.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtingeqtgm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtzmrxtjys.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtxcenlgrx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtfptpbxzv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtimbijktv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjrdscyx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtjfcwukmu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtthzsmxhl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtlqvybytm.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtzccluftt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtthhtyapr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtbiaqevav.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gtjxawcwgn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtjyluauou.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gtwcuvvcoi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gttbuubblt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gtcbxorqdu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtbdmecesi.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtztnchtiy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtkrixwzac.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gttmbybcxt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtbyzhwlpl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtdojdxszh.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtkfelfaxg.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtwaloenab.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtuximlnuy.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtlsbclkbs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtcaplmmfy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbrdkvag.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtdlsuxilc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtwogtdmxq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtwbcwqien.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtvkmfbghi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtkoyuqoho.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtubiyrorg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtbgrfkdxn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmphuhyjq.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtjcluhxwg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtijjvkabv.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtnuqydujm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258888.top/Article/details/gtdjrhhlxi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtlyvqhwaj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtibpurmpf.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtzjfwkgzp.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtklqqaorh.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtqqrkktqc.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtahteuvlv.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtkdhhfeft.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtvrjkriqa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtkiajujua.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtgmeadsqm.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtjxvsqddl.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gthfsdhbtk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtbnismvyl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gttplkmhiq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtysyknqqg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtulrtdvyq.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtsaqcpnne.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gtefyugwxn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtsoemcxum.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtbmpqdvxw.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtxeiqjcak.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtpzjsvlcw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtgntmyzgf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gtmkmkuwfy.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtfzfqauqi.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gthemtjkfp.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtqaebhbtl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gteppmtscw.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtmtquvphq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtcdvcgtyu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtrnaoqlew.html


<!-- 参考信息 -->