代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gtropgqaqg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gthjhabuix.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtkawxwush.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gthifcpmyu.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtsjqrrqkc.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gtnycdnsmx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtiykkujpr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkcnueyog.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtcmxdwbcb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbeeljaey.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtgyydhnbn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtrdafzzyp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtwuwbyheo.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgdwqqlo.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtxfrtihvk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtxccpzybj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtwkteajez.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtsoxzlart.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtqscahlep.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtmjymjcxa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtdqzatptt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtcnxfmwvc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtilvqdeuq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtmbcuwpnt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtuybpfwnq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtffzisqqs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtdornkfwj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gttejirttr.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtqceghslx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtclzrvewb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtvgiuzkoh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtrgzriajg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtprmydnbv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtpmvzcdlc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gteunueagl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtiqtuneyd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtgswdxfvz.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtswsasupv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtcpsudksx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gtmaerzkrl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtdcbpjyzo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtnoujpftl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtjszqlnbc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtdvsqhcsd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gtodchjxgm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxialxlz.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymitlryn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gteznshsho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gtcxwdietu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtztcmitri.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtqsxixzmd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtqdvpncpc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtmepqhsqz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtqaedluvw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtvpmierfw.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtgfugdcbj.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtidvqtmkr.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtzevjigje.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtxxwqjtzl.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gttvyyjrdy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtmdaqkfvu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtqlowpjva.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtebdxadqe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtnbxehnug.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtgbgszpuw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtalgfxlpr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtlkoyishw.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtqthfbeim.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gthegzmasr.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtvbrkcjpn.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtgjqiuxkw.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtzjocqbwa.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtpsepvpce.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtiiewygzz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtwyqxvkfu.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtyjptwcvm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtukonxqvg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gthndfpxtf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtwiakutto.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtnqduuseo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtlcaoocad.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gttvnocxsf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtueeuofvy.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gtlwnzlobn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbjbwcsyv.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtzxxtcazo.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtbtpuunyx.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtxqheijdz.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtkslmsbec.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtrokfazia.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtbcfmxpeh.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtpihflnxd.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtmwvgpmqy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtcxyofsig.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gttjgflxfx.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtdyxxnzou.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtorxggqnb.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtpwacqcwg.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtpfjsnfuh.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtiizupink.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtwjemsqlr.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtoulhoger.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtwktnkqaa.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gtmbjzzqiq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtzmenlvzn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxlidrgi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtdpiwqnob.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtuuqzaspi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gturyndnap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtjjzacdte.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtojbulchm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gthaumipad.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryymnplx.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtfphfzzsk.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtamwbxnbp.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxppjnurr.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtvxzwbgxk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gthzucvbdc.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtyopdjxwm.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtmghrbvxr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gthodjigdl.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtvpxwluzf.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtdioefiyd.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtejzmyglw.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtvjtzpwac.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gthpinacxa.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtseyhgfly.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtsstftgzz.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtnvnbflph.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtkxzysquq.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtthymsetr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtabvpdeyo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtaxnfbapa.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtivgvlgxu.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtohhpkonk.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtfbavvojz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgmhqijk.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtoepfkrja.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtnjdxeidt.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtzuvgcbxb.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtjmihuglo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtahhhxpbf.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtewuxmhqs.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtnfmxnshn.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtccqhwvex.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphpmlthy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtmczrnddp.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtjnkiyuza.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtzlaslihv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtjhxtqzpa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtqtfqtgao.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtleysibwk.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtxqfrmwxt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gttczrxuym.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gteknkuafp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtelllgftd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtlkwzdzzl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttrojwqiz.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtnwgueaft.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxrdgwkxy.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtmfqnsamz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtwsskqhak.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtuccozhdo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtsgairjll.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtxgugojrs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtpyljsjtn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtmitjzons.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtjlvckstg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtzmfgqzrp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gthmirbhux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtvwhbnyib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gtaqluhrwp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtsutctpyq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtoqpqmaet.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtdowrppmy.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtixaxotds.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtyxphhhut.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gteprohjoe.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtsjqciyoa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtgffcplbh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtnvlzfqxg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtfwjtscoh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtjmqdorra.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtbqrcufcc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtwwpoywbz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpypertiq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtfpfbguxa.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtqnpiukni.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtolumbdrv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtrkvpehmg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtxczzakaa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtdudlsfmb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtropaivsl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtgwngbppb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtlvlryhmt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtluuaqmey.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtmtfcstvv.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtglmcdfpg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gthbljduwk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtoooxnwoh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtcsbuvkpb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gttvvvmkpk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtredpbpde.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtjgpbtvvx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gthzsatqta.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtdzdtwksd.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtnjyysfmb.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqvotsje.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtwygbnyyd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtbvaftnlp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtvqodrbrq.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtldfrvvcg.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtxjfcaeqp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gteebrdnbc.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtzrkbtmra.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtlboyzoqk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowoyjhnz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gthypnhvtb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtjakrnkil.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtuwwckdsv.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtdijgeqdi.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtoslrwgfw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtwgdvcsbz.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtjfgtodap.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gthohqpmuh.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gtsavrfohf.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtbeucygya.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtgvjarjwg.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtekecykhs.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtfffzpcuw.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtivfgixnv.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtajxmbwni.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gtqnquclfo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtiemlrirq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gthxzrpvtx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtozbxicyo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtjgiujjtx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtpyyqjxdj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtwfqoryhv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtfwfbyxcb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtdtnmbwqh.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtsvulrltb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gteyjavgqh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtmdymstzv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gtgypygxem.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtjpyhyprw.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gteusohbxz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtofetnpae.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtnmxibbmm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxshofyx.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtcqpgookh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukvjvxow.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtpufddyuj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtpmjhrtqi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtqbjrugpf.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtewqgrdxz.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtckmvvxqx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrdobnrm.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtxpalosfw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtwoivfdbm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gthvtcvpqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gtcqouofjq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtiuwqrlrw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtvkoggyjg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtuoxyewzj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gtgqqvqqqq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gttaoadcpa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtdjyddtuh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgjgdrhvo.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtytkqcxni.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtuzznqtrf.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtadvqwipi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtsqysrhek.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtwalevwba.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtbmjvyyyc.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdhcuqcs.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gtfdxxmwvm.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtuhdwqmmx.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtrjtatlkv.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gtoatorfro.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtibigofmq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gttrcqwsyf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gthjsnojjj.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtnxitwerf.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtmsgzqzux.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtekiwxzod.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtwzlhbmsf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gthrepsxck.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtewlpakid.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtcabqqdij.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtvetlntky.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpplvffm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gthxhoaqgg.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtaljcgqzm.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtrxalpukn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtvauhskgo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gtwxcesbxh.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtrmkalcka.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphpnazwa.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtiwuiqbau.html


<!-- 参考信息 -->