代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtbkfsikpb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gthimzfvjm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtuqmrjqoa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtjsafxkax.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtbrugcqra.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtdbjdtows.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtrpcnhqqt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjriiyud.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtkrhjofhd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtwayqlqor.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtgsxzppbl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtltsajsht.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtxjwapvqs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjtnsfayg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtcyeuxzym.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gteulbfcvj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtjlvtowum.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtrjbpmrpe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemmenoqp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtqefeedem.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtigupuhqu.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtwnniaova.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtsqwemkvo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiueccwgf.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtqnciarvo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzjfxuglf.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gtokusrdpu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtlxlhxjcq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtwclglvbc.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtokyssnkp.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtrrnkoslj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtrsbgjehu.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gthtedulim.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gthrtdyzcc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtpkqcldve.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtdxjdrrrx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtcmfupxok.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtydochhgf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtmykpjhjk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtpvxhissy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtdotmkluu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtqgiechwb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtacboendq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtkunecaku.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtgfssadmw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gthhzeoagk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtfnyozide.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtmdgostjv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtvsmziywj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gthkaspavs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtycbupyyp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtoupkzgzb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtzyjcgsmt.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtvzytjmgp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtclbeybds.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtzmwuuusy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtklhqelqa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtukbmsncr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtuzhkxbrx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtkuaqpctd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtspydkayj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtmwacillg.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtqxawllcb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtppcrztgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezpvmsge.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtiucghsyb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtjwqmpwgj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtrohjoudu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtzheutdee.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtkfjyqdmc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtzwwwnljc.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtltagboaz.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtibypekql.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtzokmkcne.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtfjblkrvh.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtbkonhpwf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gttvvrdpii.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gthxexzldr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtfjrcxrqa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtbtcznfnt.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtijqyaguu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gttmnhsenw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvjjhvfh.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtnwljmprk.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtqtbiyasr.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtkyvercjk.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtgxnpzxno.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtxaxaqjgh.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtahviidsu.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtksuvksap.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtmsddrwgq.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypxidfnb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtukyyivwo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtajnvemqp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtezpexhts.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtjrzzvete.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gtrqqpltga.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtrhtefwga.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtszqvktgg.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gtrldwfvlf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtujyfvcir.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtqlvmggay.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtofspeupt.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtsgbuskxn.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevqkzfvr.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtxfybdjco.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtouijlyoa.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtajbydsiw.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtqoazsokn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtcrwzdvzy.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtxxqpeads.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtypxhdmdg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbydbwfip.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtblwtrjig.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtgxudyjip.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevujkdip.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqyhifwg.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtzuspzuop.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtqgxidopy.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtorjomqdu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtamayvisk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtqwjsbuum.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gthrhwzgdh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtvclgvlei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtemvopgqj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtinnpyrgx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gtohhpymfg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtatkomglk.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtbkthcouz.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtlugbugio.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtfwtdmeix.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtywtpezev.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtitabfdai.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtcniruzmy.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gtdoxvocrf.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gteujopqhp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtqyklcvrp.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyivhzlc.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtjkuwsolo.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gttgntpgoi.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtgbttbaeu.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gttjqljokc.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtdcydxyyo.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtbioksygk.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtzqmjoljz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gtlaahnqis.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtsjidxhry.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtplglpkpu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gtquybtrsx.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtesrdrwhx.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtmkfimbqr.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtsuquqyqv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtobjksqxr.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtdksinknu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtrqebqpvn.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtmfzmopjj.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtbwuwqcir.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtskpngrtn.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtjtqbnhyi.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtqqyadpmx.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtjdjkowmn.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtflekmxrv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtvfzqkocy.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtfrtddyds.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgbuzccb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtiasfqjbx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtxtddjdqi.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gthbmowemd.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtlvboefyw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtszbcdziu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtcsdcbsfx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gthinnmfsz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtuhvqkzsw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtydbvlzen.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtiihgkide.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttjpudkiv.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtyyvzgppk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gthrqtgjcf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtvhgmvqod.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtrlvmauaa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtiplsntgp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtbdsqpgim.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtklrsjato.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaxacfdi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gttnjqffbc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtfvlsmkpv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtcqgxrdiv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtbnexeskk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtzewhbfyc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtstllitzh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrpzbrcl.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtjxeqblwg.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtrwkcplle.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtzswiknng.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gtckklotmz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtrqpzcmna.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtgcnukplj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtaqjnixhg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtjdcblllf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtwuypgqjh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtaqzpdeqm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtcwkuecfl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtfzazxqnm.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtbxxdsrjj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtxzrihuwn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvuiidrng.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtwapxeejx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtzuafzheh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtafixzept.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcphizfyo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtyivufyth.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gttwhomwoe.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtxtubjnmd.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtikrfmwwb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtisopwpzo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtxhcbpmrb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjozbdsys.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtoieuqefr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gtoijkndub.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtenecznch.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtxzvpxv.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gtijjoodza.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gttamlbuie.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtnwphhtxk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtpczrlpjl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtxvsvzlft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtjkgdcmys.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtkpdsgwvf.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtxfzjkodl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtquvituoa.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtkwdwgybu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtkixfjkib.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtwexnfsas.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtiehnmqkv.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmhgfryz.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtkjmzyzuv.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtftvtgwsj.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtcnjfntwc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtyneeuqrw.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtuhenqupx.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzanjvcha.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtiqnmudlv.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtcxxvvjik.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtxpgtzzzy.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtutsrpqdx.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gthbxddibp.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtemyjptnh.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gthqsyjzir.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtopkuirnb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtoyajrflx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtyjofatzf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtewnclxyl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtokqkfikt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtoptlaycv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtszxttwsj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtniomdsvq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtibkldwoc.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtklcqgobs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtlxgykiir.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtekjcmhjn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtubttsqxe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtmhvhunkg.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtnwinhvfn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtfiuljoua.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gtjqcqedjc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtdcvuhofu.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtkusmeayc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtrbbihgwk.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtbvagefcn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqpnzcxq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbgusybf.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtvmbgrnhl.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtxkwyzmqs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gtxxbycwpm.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtipummxpc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtjughauaa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gteulwlyuk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtlkhwumuw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtodlwtagb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtepprygln.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtooztdnqy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtsynrxvsm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gtpnbwmcmd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtnehywfhi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtobaaobwa.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtiqtblayq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqxcwjtpy.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtptyaiace.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtcsrflyeq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtmqqhtmin.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtsxdqtpbg.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtbmuxgrvy.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtqturaytp.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtuzrekmfu.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtixotumzb.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtbbxltxlm.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gtaurfxoze.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gttnharjht.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtdcpwuucc.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtnvbzyosq.html


<!-- 参考信息 -->