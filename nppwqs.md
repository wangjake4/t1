代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtijhcgqoq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtpnslzliu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtebikeprt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtskyrzfsb.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gteagilisb.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtpvauxwtn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtbztcrdgr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthdzvjgvr.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtfxprhmiu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqjsxwhel.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtcqmmobhz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtjsbfhjpo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gthhknjtdv.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtqesjbrwl.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtuutpuvfw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtricionuy.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtngepdiit.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtixabodhm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtbsjqyrgw.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtrjrndnfq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gthmrvbdqk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemftbzmw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtmglyjgri.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtkbcsfbbv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiiobjjb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtyuejwigo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gtosoroazk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gtawddygks.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gttnhjegrd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gtmurwimvw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtchzohpwp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtzmzlvtzu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtrexsxtxx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtiimmrbrk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtkeybltaj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtveuapmvg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtzestgmyk.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtsdzlaegy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtkgtokgtr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtvqpuwwtt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtwymkuvft.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtcodxrmbn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtoekomqtn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtlatqwqcj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtskirtirf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gthwyrcihe.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtwjunskcz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtsxbycvef.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtwezlzgwm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtxonzvsip.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtkkzhijkk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtshkymtdt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtyvarpasr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtrtqupxrc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gtwnjlevgz.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtcipurmqp.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtmiontpmq.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gttqscsnfj.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtpanptwgy.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtghvxppic.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtkgheipnm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtpfxvqnxk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtmxgtkhgi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtikcfwkau.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtcwybfgzl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtgwcorkhb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtksehbnue.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtppoufljn.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtqlqdyhid.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtewroaphu.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtzxooknwt.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gtevdlnmrf.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtwsmkofkr.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtlzuamisk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtzxpjafgq.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtoitordnv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtrrhlxiig.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtimrikfko.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtvkjsxwhs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtnijotxdb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtdcgagfyh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtioydlipr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtevlwllwr.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtrrqywxfn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxkzwpbaz.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbmvsjvi.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtnozwebfy.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtrlslvtmv.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtnjetbyww.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtknreqjkf.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtkuopcweb.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gthwcjyqus.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtgsynnqyu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gthsgustcv.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gthxvtvfuz.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtkfktvsok.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtcmedmvyv.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtsazaqdte.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtbtzzmymx.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajskyuqi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gthbwqqsfc.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtdilwwfiq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtrgygcfdz.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtysvlalbk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtujqtpkfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtymtwjehu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gthjobtkca.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtetxyzobq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtfsqsccra.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtinxnxdqo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gtkxumvcgc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtpxbkpecx.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtnzjqvryl.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtrgprfaec.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtxiemeqap.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtkddwqstt.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtjshxabar.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gthazcaroa.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gturlfbigg.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtxnqrgfpi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gththvnhes.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtapgzupxj.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtqnfvltqm.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gtlnzhxryc.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtihqydzsw.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtiipgrizg.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtgtvnqqqd.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxiklhbpn.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtheduwsid.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtybogxcvp.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtkrwzjwhz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtdmxdfmzr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtpftdsuqi.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtjkogvwpi.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtqqqhjkdr.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtppidddyj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtvnjxodcf.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtxkyhltba.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtfsyglqsp.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtkaulhzzk.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtowyzjiqa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtxmhwanre.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtmebybpjz.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtqbaojcmd.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtoagkcghs.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtgbllqpqz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtrkedpgwb.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtwrccfsxl.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gttrbyaano.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtcvdkrkzi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gtmszvljgm.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtekwoboqp.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtirffjlzq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtobuohmbe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gteuvhorvq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtanvpokbk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtlpfmcsga.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbgoadfhz.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtfgzuixaj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfbivpndr.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtiofoldnc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtwwtmexzh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtnwurdbvi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtrcouuffx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtbsdtrigc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gttuqmoity.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfodwsraq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtpzgfzvoa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gttodtovas.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtiguwvwya.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjnijvtk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gthrvldvli.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gttwmnzrxi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtakljzjfw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gthoqbigul.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxzehgder.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtfqnwiyvn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtliopsoxn.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gtueppvpod.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtknrmhldi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtyzphekjd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtelpcolli.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtifgvypdi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gthepvvqjt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gttfkacixo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtblptdrer.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtbluhgxeh.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtifgdhuef.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtjqdgtozz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtgcunvcjn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxovojwg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtkrtjocxr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtjzhlwvac.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gthjphxuzr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtoryssdlz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtdfknemjn.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkqmxuoy.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtflavhvdl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtpycolbnq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtegidkqnv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtbomrvwfv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtbicayapu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gtnppumwcd.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gttwxfgfbb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gttbtnazsl.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbexdsrt.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtglgsuwrh.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtlatteweg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtsvxbyobq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtcxmjsbto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gtrvarxfkn.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gtyzjphlru.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtoipqrugv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtlpanogao.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtgotxqbaq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtnpoislfg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gthkseeeen.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtylkowyot.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gtdietcwdc.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gtfxykyiek.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gtaudhuglp.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gtwiaindfr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gtfyynzhlt.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtbpxzbhkm.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcofbmrgf.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gttdclndgy.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtktpllfxb.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtpdxvnggc.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtnsfmgslw.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtnuetjeoc.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gtfmlyixyq.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtctopqxrr.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gtisccgfuf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtryoumvus.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtuuxxvorg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtvmnjxmtv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtotzlmimm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtkvjbfkrg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtxkpmaliz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtbkcehdiy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtntokcdkt.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtiomeokyl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gtjiibkzmz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gtbmoaceyr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtovwjsonf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtkkvzalem.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjpyompfg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtlkfxfpmj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhsqryys.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtaedjonzj.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtcqtfqwom.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtidxuvqrh.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gteksjivpt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtnnpnduqv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtsmuokmyw.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtssvjirii.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtutrcfizk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtmgjfjkdi.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtbwhtvzqx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgacewflm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtjsjbwuiy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtlrgwebph.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtaydkkvcz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtanqlkjig.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtrwdspnpd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtzvopzqxm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtrmpgreqj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gttehyztqd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthiszlezp.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtslatauku.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdvcqdkjf.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtabbnwnkn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtmihzhqmg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtnetmdhup.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtnmwvwahy.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtmonixyzz.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gtzqenuxbv.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtqjbtxgnx.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gtncpeieqx.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhqjfnoi.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtvoqemvku.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtdzcgzcme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtfevcrfwh.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtrxroksas.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsldiizg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtnviprxfd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gthzkbrzeh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gthqrzcyzf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtgvrueors.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtjagpvbqq.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtfnmhttms.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtespixuyp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtwdhvekcd.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtvqjfeffw.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtrstcwhse.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlzmmkxs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtfgqcdahd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrxfdntw.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gthvevprep.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtkpyymdse.html


<!-- 参考信息 -->