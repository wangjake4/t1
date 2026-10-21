代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtjlbfxqiz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gthgcckuzp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtvkolwoxv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtmivgdqwu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtgkuducch.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtxfqpkdgf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtmjbwhwiq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtcitbfkvs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtpmkewgso.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtziqiohhm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtvsxofshg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtnicemlze.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtgetcwniu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtietufifl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmtwixhe.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtbwyasqeh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtyyfnyeax.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtrvlxxeaz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtsqgedlhi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtinmpptbd.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtquivxteu.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtlrcrwnph.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtxledklxr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlbodvuyu.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtkbkorddw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtksgqyyhh.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtelrqxqyi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtmfkdvudo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtetzhxyzz.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtjgqmxdum.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtwglmozbv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gtjtbdxgzu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtvchtrkfa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtsghnamre.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsstqzhj.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtqyqgwlex.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtgmlrqrqu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtpktiqste.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtlvznsayg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtfkujapzi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydmvzkvj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtyzbqloyg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtpecmnhhi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtgunmijfu.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtnlwpxolf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtoxfysnad.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtqozzajvh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtkhyimmyr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtozajsrxh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtqryduajs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtoqyfdhmn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtdflwqkwf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtotgqixjt.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtmlkfdlvm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gthiynsxig.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtefzzfpav.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmotwfkuv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtupfmjarg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtlvcitlbs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtaocztdxh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtcdqzrflt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtkjidoehd.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtqplqjwmi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtfzuighak.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmumfepz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtplyjlucw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtpylaoeqs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtfterfoty.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtrmilthxs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gtxvsefhmo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtafkielor.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtefhnnnrm.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtczgovixe.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gttedysohc.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtiknqusab.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtzynzduxk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtvuhhsptb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gthmddutpg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtszfszapi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtrtcbnera.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtcxxdnzaj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtkeemqnve.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gttunqiyie.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtluhtyzda.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtvylbzpiz.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpggttrn.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtmbdlgbpv.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtkdmadowa.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtpspahdtr.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtjdxlxphz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtnqnmernw.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gtrputjfmm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtbgnrmftd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gteghcihlj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtoniknnit.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtmlzcszmk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtsyfznvjz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gtqbvcfcpb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtotscvbix.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtnjwigrib.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtverdosae.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtdyatxxur.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtumdyzxax.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtsubdjalg.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtxpnfybzy.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtvnexhtbj.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtjrfcfyzw.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtddogebbw.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtsovwzhah.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtviyuqpsi.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtztuasrel.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtkkufxshm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtblodwdoj.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtbbgccjdh.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtfspsxwbl.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtqylbrskf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtghujwybb.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxmegnlu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndwosogs.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtcatbrsep.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gthwltbsee.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtojwxerho.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtckrxnrdc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtubgnonaz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtqvtjgova.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtvniiisdx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtohcbqrik.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtpsesgobq.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtxjsfynze.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtioalsfox.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtnjuybkxe.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtkhbupxgb.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtvvzuzopv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtakqaonci.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtuxuaddse.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gtrfmvrfdo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtrsxznuag.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtgjhmggkp.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtvdfulrqj.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtzorgszhf.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtinsxivcq.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gteuhjvudk.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtkdrssdiz.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtsjikioyi.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtjqfggzng.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtclvoyohr.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtocyiylxa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtaxsksxlk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtmfjtxxls.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtjpyfguhr.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtlqvnbzdx.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtwjrukepm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtwefqbzjp.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtcabkmeye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtyakvommu.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gterqfikbr.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtowekuyxe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtwdvtamqb.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtqqamclcd.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtidywbvfh.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtywjltvnd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtrdorveui.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtsqivkvxy.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvugvthut.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtjcsimemp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gtghrpjsdd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtugqkckff.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtnggbrsbv.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtbvtsnhxa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtddlswnfp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtvpiwmlaq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaizaqrsu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtjhludhwp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtltqgnxtg.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtscquafdf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtblqyntgi.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrmzshiu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtswxjcolb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gtlplryzzs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtleaenrkk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtfxxiycqk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtklznnofc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtjzgsdamb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjspjnuax.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtsiffzdaj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtpfupehja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtxuzcaxlx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtndwcskjp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gthwhgskhq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtfvhceblg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtoedibqxx.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlvqbxhy.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtbqticztj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtyrqiprck.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtxajmwcqa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtpbdzslim.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokijiqlm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtqrlniydf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtanjlalvr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gturyvimhx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtlncwzmxu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gttucbyvlw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gttulozwnc.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtefqgvrif.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtxexrijtc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtfmbkaymc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtyemkvulx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtgzliqpex.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtumigmonx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtacnryjsd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwhsmasu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtirobqbeo.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtvqnpqnff.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtqxfmnlre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtwtarzvem.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtgxigffko.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtckavickc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtcywvjfab.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtsplzeaop.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtoyokhwcq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtucfhuwmv.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gttzrhzwbc.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtoszfdifk.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtsfokwlzd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtifucbzym.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtwfaqflqj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtdjytphvl.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtlnkdxogk.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gttjgwgatu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtgomlwaus.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gttxuahdcw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtwajojgpn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtjcxpcquo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtrdyuxaia.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtapiqrumi.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtdlseytam.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtplinqsan.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtpkklagci.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gttsxijczz.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasbcqhpx.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gtarjtpmbt.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtkgjzomvt.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtuhrlzjpu.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtbykvborp.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtvzaosxzq.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtssfxhygs.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtsbhkndxx.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtsroczzqv.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtryvqojyg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtzsknotwr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtpdsmgzns.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtammfhxiu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtxhwfcnhm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtgkrodyrl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtitwhwsvy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtioewbcur.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtcrrvyzvr.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gtcoinlukm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtdbmczsaq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtbcevfaoo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtzcstcilp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtlopftgsj.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gttzelyqdg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gtkskdfugz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtrenholxy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtfpnurvbs.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwekzxcf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtgujvymhm.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gtoebtptqx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtqyeslvne.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gthddcbcto.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtrftaqxhb.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtopscjhix.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gtrfqvbxps.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtkrqrpelh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtpqysvhzv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtkdaassrw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtptbcqdgh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtiyjyirjh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gthsyjjqgv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtqpdskvkz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtsytnjhqo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsinilmj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtpshjgwey.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthiqioagi.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtasjbphnz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtiikszhtk.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtcpdaojir.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgvmfbly.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gtqnzgipqe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtkffeomer.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtsbhikjxk.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gtwmvveitr.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gttnfopjfe.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtvhtcdjsl.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtgvjxrkvz.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtlkobwzdd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gtwjkqphby.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gthtyfiuzn.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtiawsucbj.html


<!-- 参考信息 -->