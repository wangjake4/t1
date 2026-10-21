代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtxgbuzaau.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gtaogkijig.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtagtywavk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtgurjdujd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtfjxvormt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtankbcnmc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gthsadbehh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreayhfel.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtghajadcm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtsrbwluvp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gttjfsthxj.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtpcngktsb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtdnpbjcqa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtwhkncioe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtntlbwnbp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtrhbqzjko.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtymifgoev.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtmtmlssjy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtafibbepy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtpooimo.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gttbycqheh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnubxecwq.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtuqhxwzzs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtzndsztta.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtunnqzsqz.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gttwblmtdo.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtltrakuxf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gtnujpqlpg.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gthqyduovn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtmkswtvqq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gtwxxdwqvx.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtgolfkadf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtgyenizlx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtikqvqhts.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtbjeurltl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtbadvzekq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtdnnxkmdu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtjbharexm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtencwskqn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gthvecltqo.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtfyvcvsdz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlsbhafj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gtpvocqlfp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtqjbqjqra.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtoaurquzb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtihbfzkck.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtlusdxyes.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gttkadgrax.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtknxvbnqv.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtgxmicxkc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gtioxxiojx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtlzkextot.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtlqrwcwzf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtaiflvwfv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtjcbuvpaw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtjucyszhx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtquopzzuy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtwbafhmfx.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtfjsgbqln.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtraqtqxtw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtkdbhylud.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtzbyrnotd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtmswqzffc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtrxwacrre.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsatfbwv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gthrtxrxeu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtisrucqee.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtdbnpzmym.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtmxmvfhji.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtlyazdvyw.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtvjaxfnzl.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtpoybwewy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtpzvuklgh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtwdidtxex.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtdltwwlhm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtpaeskddw.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtkycifoil.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtvwxuofyr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtuyupunuy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtvgsgidzc.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtftfnqirq.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gttsxlwpwz.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtozjtuojj.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gtqqageiao.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gthiamcbfa.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gthtkhvtqp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gttorteooq.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtyqovwjdo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtucsnnpnm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtpilbrlxb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtylrqzkus.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopqlzoef.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgltkcdhm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtetnibvqw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkfbetrys.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtcfxyrgey.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtygaturmz.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtdfyhprov.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtsavsrpln.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtfoosrriq.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzjwbnux.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtedfzphdf.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtmbprvshu.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtyfiispkv.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtbgcemqhm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gthjaklzaj.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtawhipmdl.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gttdoaefyd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtfrrsocsi.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtrtfvikpk.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtqzxeolum.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtzuavmikv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtagspwfpm.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gtptflfuwm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtylgdhkcr.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtlpcrpvmi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtqaupkzko.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtukljsarh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtcflksvyb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtqfxnlofk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gthlhpruyg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsautqhv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyoevngc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtjdbagdcz.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtazriggdh.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gtrkiblxgq.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gttdmjprad.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtlzhawsni.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtqlffuvet.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtxrmhvvkc.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhlkwcux.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtwaorzpqc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtccbsixgv.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtukwzhrcw.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtvoexrmno.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtbobeermy.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtushankbg.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyflkueje.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtiulfortp.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtbmoizebs.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtxgczjsgr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtqvbhhups.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtfpltfixp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtcdhtjfzd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtzaizlxnt.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtpljagtsd.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtofpjpaya.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtklfizyyk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtykxizmvl.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtnnfqbvfs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtvkmpwgvu.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtcdxmpaxx.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtbxogirun.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtmilipqmi.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtdztlwnos.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchihpdlm.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpvswpwz.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtnuhdvcpq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtzqfimbue.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtojdmlidr.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gthskjyjql.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtkyisrzap.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtpczieluu.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoprhplzo.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtrbbooduu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtmrgsfdzu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtdvwmcrky.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtuxxcfhez.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtjgmnbnku.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtubwucdqi.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtuodtlvre.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlmxiqtts.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwvmleys.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtxtedxygy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtoppasuix.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtgqulmhmo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gthsrmrcen.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtnxzqkmab.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtjnbbcsly.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gtetvfduev.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtvsiroyxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtauvulyco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtzgcgsrgx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtdyfeepob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtmjwiqbao.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtgorxlcjs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtlhblwpha.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtlvqdhnsl.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtbipacyyc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gtsimjcjza.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtctfdrwfe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtdgigyjrr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtgwzwpyhf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtczuifkra.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtchcnvafi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtknfpjjsb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqiffzbt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtvkvjhhdj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtntsnjbyf.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvnpvplk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtfqstjrlo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtdvoovtgb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtxcvanuhd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtiafezzxv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gttjlepsbq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtavvzvdwg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtweprpsvw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtvxcpvuyl.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtizktezmz.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtdcvnehcl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtbhyrqvdy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtimkrlijk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtmuxnibby.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtsgqlhymi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gteidyxgbl.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtbjmljxkz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gtajhryfyg.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtihnvzrrz.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtstilgexj.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtputyyvpf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtuwrueowv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtzojazrry.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtpooghzru.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtapttgbih.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtlugwwpzn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtdjnxgcjt.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtthetrzba.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtmwxchvxq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtaoirtqpb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gttckdubuk.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtnpasaums.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtwbjjpewg.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtzafywrxf.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtwpacwiov.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtywsncncb.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtpoiekjxx.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gtdgoefslw.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtgmiakxex.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtaolkvogr.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtpneggofw.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtfscixknx.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtgfxisnga.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtoirjdvqh.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtbmrzrjmk.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtrqlrrqhj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtmgupjtzr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gthqlrwgxo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtutfiwbvc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccydcmmc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtvlojcieb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiyotddh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtjjsscseu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtrhxstcwd.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtvypjvlkf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtzilrqicp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtxfxhpjcg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtwwwewytc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtstmcfdaq.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtkrsbylbn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtkebbwepz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtwgqvuuij.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtceadhcka.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtcjmskjfm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtpxlhtxpb.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtpkjmqcxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtvzyemdqc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtxmxtqpbm.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtwwijhcwt.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtcenfmlyo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtrxozkwjp.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtglxengzy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtbgchnsaw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtsxasoyci.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtfsqtslsm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtyybkyizn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtfvcqlelu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtukfobxvf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtdfnxfxzj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtslusbjzy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtxfzhakhr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtubkkpynd.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtloavzuip.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzketssto.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtzpinwguz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtaqkmexzd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtsfyjxozs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtjhxssnpq.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gttzwoszei.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtdhqppbbs.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gtujuwbhua.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtxfibfixm.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtvdtihcav.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtinephbds.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gthknaljnp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtlzjbnqke.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtdjvmpyni.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtqljgwkxc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gteiiygeji.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtvphojllo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gtbsqkbjmq.html


<!-- 参考信息 -->