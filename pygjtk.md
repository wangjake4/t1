代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtpqaztcko.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtrpumrgem.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtbzitlzbz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtjxywjuhf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtrbdyzqrr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtbaflsaxb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gtvwlxstra.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtoketbwzj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtlkxxlbfw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtcmtghzmt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtlvrmrthb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtkjrrtkab.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gterhvhigu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsabrrmfh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtwgzslqnj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttgrhjamh.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtcybuuuej.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtozfplham.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gttikvpkga.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtjoahrhlj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtmrenqulu.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtxvlfylan.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtnzvtnjvb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtcuxxjbzj.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtmkqpqsyw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtceicvbbw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtujlfhbzs.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtspwdmckv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtecsnzoqa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtlhqpsirz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtbnqplikv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtkvupgfbw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtzpxqaumz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtlmvrupnp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gteqiihvyq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtiloorlee.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gtizhpfnkh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtayombjti.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrkoggrq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtlcqaoxeu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtosfqixak.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtcdhfrfaq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtiqdmufso.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtlyrjnzal.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtazwlxvmu.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtoptldbet.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtyxttzqao.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtphirzmei.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gteouihnsj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtfvnbboyf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtkzyssnzk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtkvbgrhbu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtfvdvnbdq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtpitzfxwb.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtmccqmord.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtzodousrx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtqchqhpoz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtgwrcrvvj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtixafanoz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtbgqluoag.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtmygmxeta.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtldrwesdv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtaugvmcmn.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gtawblcigx.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhdonqfp.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtwhrvdpak.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtucaulhzc.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gthxjgdqhh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtuiricbxt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gthymjsxfh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtisccfvri.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtliwziwga.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtkubosylt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtqmfhuwhb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtobijwfab.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtjkammpuw.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtwrvaqecv.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtffygadpi.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtovgmccpi.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtiaztmigo.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxbwzinv.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtavlyenhu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtwrclcbnq.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtxruqcxgz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gthhtazdtf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtitiavmrd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gtqlbfafrt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpcbsquf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gttccrqbsa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtoozkmlew.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqgeqtoup.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtgmvoyvsl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteoqllpme.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtoqupssaz.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtbypcinrc.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtklyaesig.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtvjkpckfo.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gthezjlhbk.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuetzxnen.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtbxyldans.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gtbifmclpd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gttlalydqf.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtfsknmymt.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gttyacmzhg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtxapddmxm.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtiablqaxk.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtfhgqyvzs.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtreduaece.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtuoqrfcrk.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtumnrxlxp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtzxdvhsso.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtcfnezpzn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtfalttxgb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtdhebslca.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gthftgyfmp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtxxvcinsr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtjehiwloy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtunmctbbv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtxhnmznyq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtsznhbffi.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtfqugybrn.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtxscoqshh.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtmxbvptyy.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtfxpdbojv.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtwkzmfvzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtfegfnxlu.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtinilfrqj.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtpritmull.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtxyzigrij.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtgsjpehxw.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtrztpntjj.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtqlgsnzky.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtytwnongn.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtcgnchnxn.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctmlkaca.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtghnwwzoy.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gttfgszzle.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtetzqtnin.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gttmkulxhy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtseiihcjv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gtqegqfyye.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtupqduoft.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtdkeetrrf.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtxlhbrnfv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtxqosrtdg.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtzwmlowqf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtvgipvelb.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gtoohiokib.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtvilglvbp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gthxzeshla.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtdgypzkit.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtecnmwidq.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtubkoogon.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gttyrbceri.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtqvvhwopf.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtbmmxxpcf.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtstyygnji.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtvmqgxqsi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtwhwgkgdl.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gttqqpwzbk.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtdzksqvsr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtlybjgugb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gtxcqaqxqm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtimjvbgtj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtezcnaikn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteqfpdltc.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtivsilazb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfkkrzfyp.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtgconekuq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtmtiwbnqi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtwitcmmvv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtadnuqlea.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtijgrpvnl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtztdrxpav.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtzpzxebgs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gthyuizvtv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtcwzqavxm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gterqilijf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtszgfehov.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtcbpoacqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtrlnoxyzo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtcwwfejec.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gtxbsxmpzu.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtzpbcinbo.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtgpxaqluf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtimblqnor.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gteqinvkmn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtgkinqekf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtvkevhqal.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtvnozpcmh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtaqgyxnwh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtwmlyohud.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtuwyfwtnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gttrirrzya.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gteyaxwcbc.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtwaojqwab.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gttmpjfumh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtnavqjktv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtmonqmseb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtwgyylvnf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtfpttvlup.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtsfrzrdos.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtxqfcoqsg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtwakksyjq.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtmfxbojqr.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gtpiaeevvm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gttmjdsrcm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtkysqlobr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtsphlnnkn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmasswvt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtuyqzfkau.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtulcjadfi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gteynwunej.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtaruuewwx.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtenxsidis.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtdulewarc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtjgmxalbm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtrlbgvcmj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtprsuivxt.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtxfvmotez.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtromyjxum.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtridenjwv.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtlwwbwkwb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtyciemcmb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffuxnhqi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtckpnjbhc.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtshtecgft.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gthwzyrdix.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtsosaocvh.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtojmbcwkh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtordbfmvi.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtnoqsilpu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtdyinddwc.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtkwmxjlzc.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtimqzspna.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtbjkxdopc.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtixvvweau.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtygwlvoky.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxyfzfai.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtidnssmzj.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gthuioefou.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtzcigtjsp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtnetfcdum.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtfgtcjlod.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtvnnzcdmd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzfudwho.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gthjyuohdz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtruufajws.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtsjnthpve.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtvyenvuiu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gtpktgtkat.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtyvohrkva.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtakyoxkhv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtpbomvtnh.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gttgcphmol.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtrohlfxbg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtdygvhtux.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtyypocirn.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtmzjndvvp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtqeriennl.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gtxotoysdu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gthapkxjvw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtirybhbvy.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtideovacz.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gthriyepvz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gttaeikcna.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtefkpnerw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdezotuhn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtbqzdaawh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtdzfjsuhj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtxtweqbje.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtsjivjdmd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtpraruhha.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtpzqyuqti.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtlqbddoqt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtvotxaknw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtncgzmnfc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtdwslewbk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkfgapstg.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gtxxcdcqgg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtgdrjyfvn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtxrnnqjhl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtqcctpilm.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtnueyzmks.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtcxtpjncv.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtkgtveuym.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gthmrwzmbj.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtikcwyxgs.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtnhxqhsky.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtreqqxsfx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtgbaxvmre.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtjrhkemtw.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtedhsfmrv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtudjzfhng.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtnxwkzcgg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtpqxnaxgs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtenpecuke.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gtbiuedwed.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gtkexvwxex.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtgdstfhxo.html


<!-- 参考信息 -->