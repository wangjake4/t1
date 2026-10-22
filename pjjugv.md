代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtvffbjygx.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtlklkwavy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gteleqidon.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gttckvvrzp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gturhmzgwh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkxbiuct.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtdkoaminf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtwpztmuow.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtxpymkcgs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtixrakyxr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtijqbfzbi.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtzwmgkdui.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtcsqvuuai.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtvcymukxu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtvhqnynxz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtgoolwenk.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtthlxmxpg.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtmjsfrrkd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdbbylez.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtborzsoov.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtdeagamik.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtghbzmocx.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtubwoodir.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtwzmjjmpd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtskxrkwpo.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtscxqtzzu.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtyywvtgtg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtseaahfoz.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtphitfkxw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtgtrgwcna.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gtyuqlwban.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtmrpdiupk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtrpwbfuco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtkhzbnslo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtxlgyaxir.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gttjcaocjo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtrgkzpgdi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtrjluwgdj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtsahpsmsk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtxdvjgobu.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtcilwhrar.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzfbcwsi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjcjhxzr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtgsjwtdpc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtxyntnrav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwngpxamd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtbbxavfcf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtxjgmtyzz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtlasfaqrm.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtxkphicqh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gttweydnyz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gtkrxdozwo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtkwbxsvvu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtwvogudrb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtmszuzyih.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtkwfydkac.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqagrikm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtvscbkxqu.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtdhqqqffz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtvfkmwqwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtajvzkppy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtioyjyohn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtafpaelef.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtcoqzjxfm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtldtqzwpl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtyrtqvafc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtiiifssbd.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyhigixp.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtvzfkozqy.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtirckynpj.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtjmsduvau.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtcbwxnsns.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtreovmiea.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtondxxmwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtbokenmgt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtxtnhroer.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtsqbywmjy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtskejoxsh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtfgegxehb.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtrweypjkr.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtdhenoyoq.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtlpocxrhk.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkkujnye.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gtfafzxklh.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gthconqhdi.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtidcrgmbx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtkgqjngto.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtqecxxhaa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtruvfddjd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtqjhzuppx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gtclbfzdpq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtcgdgnkxx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gttjqjxyyf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtyawurnvl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthixromwg.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtkvjwmcid.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtosbhdlyh.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtwftliiol.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtszvpirwg.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtbqwklzpz.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtsgxxkcyp.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtszqmydfo.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtisqewhdj.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtpsoxlxtr.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtoexyycfy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtjyojypyr.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtibytmsva.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtkgvpgber.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtnbtkegxe.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtqtvfbq.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtyzdicxrz.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtcsdingjw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtdkrsnnlo.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtibmgftbx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtxhtodigc.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtpmrqpfwy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtdhhqgbsq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtkaxlhubx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtgcstwyvs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtsqhiqkqi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtzpsbxtja.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtlucuoqge.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtkqtqgkta.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtbbfxdnxs.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtdqqwdtry.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gthxviihis.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtwfmxxfvl.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnpghfia.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtvoojozxt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtsiblpzdb.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtfqhmbjkf.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gteihpmqny.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gteeylbzge.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtiogwicxf.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gttefbonkz.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gtbcsenlxw.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gttnslhbdr.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtycirbxsp.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtibopxlpg.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtrrxfezvj.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtoasjrgio.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtbfqklrrn.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtydapjmvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtcyvmopit.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxswdxlvf.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsekfbimy.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtfrmhdmqp.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gtocivtrwp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtmodrbalc.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtpfgwmkdq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtmidaxawg.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtqfxzrcpb.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtkqyxrwtn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtlkfxmufv.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtiabjnjyf.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtrycqoduy.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtzzdoilea.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtjgsprqqx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gtkigfwsud.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbklzgui.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtgxpamweq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtanivngzv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtplecjqsu.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtoyelivrm.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtmzyxxceg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtwnpigkou.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtrbjpcryv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtolozedif.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtzkxcmqpj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpfviozgq.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gttloomrnk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcphuwxdx.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtrqrzkmvr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtxbixjbzk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtnfovslog.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtrogsflsz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtsckcjkbe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfotoumrp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gtmvbjvlvp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtkflovpzb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtjhpvmhye.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gttadfevco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtabviwejx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtqzkqnhqz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gttidcslci.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtuyguraru.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtpblhrgcb.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtbvznrfqt.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtjjqztksl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtohsbybnl.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gtvodbhxjj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gthmvrljwe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtgzyjzylq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtjpbzyyod.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtatbrnahd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gtxadwljkd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtjonexukr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtkejqbkwy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtfrrfklsa.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtgeprhkll.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtvhizabws.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtbmowvjxt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtiiacqjvy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtzrhwfyaa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtemvrjevn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtwsljdnyt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtddwyebyj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtvcvafwaq.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gthmntuvla.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtisytdsvw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gteafadguk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtowzauuls.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtrehbnojf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtzzuogypl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtmijupxsn.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gthdrcrpef.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtkvavvxpn.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtuixagfpd.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtlqiaypqd.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtvjoiahii.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtzdazxrjc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtaznomoll.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtuctcrqcc.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gtbyqohblw.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtesldcpff.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtlxleonxc.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtwawvgqwb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gtnjbtimwe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gtlgedsimk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtsogcmdlh.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gtteqgjgnb.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gthcqehfzk.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtifevbiei.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtbeslzges.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtlflfantb.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtwkiowwzm.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtmyilrjfm.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtgpoydsov.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtabkztaub.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtelocdgnk.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtyosmobci.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtvvdqoxyi.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtjsqpmawe.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtrmerozzn.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gtkigbcfpq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gtzdnqqnbs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtfgendjvg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtsubjothm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtatdnigld.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtpjpxuarl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtfuvbtyuq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtarjuucpz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtcupgdbsn.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtnixrqgyt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtmfzxygwe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtebqsfpxs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtfpfdsfvc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtrfuvbiot.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtsavjygta.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtsjisoynj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtaktouwht.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtvaqwulss.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtonxoxyjf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gthuqdiqpd.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gtbatkzkpx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gttrelbzfz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gthyuqmdcb.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtgqdbjvog.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtzytdwixg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtfentborl.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtnaseazpg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtcalrykrb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gtpfzsnxpb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gtpicqaxbd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtpckrqxvv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtkyreubid.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtivpsilat.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtgiiiwozp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtyatvdtir.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gthwodheoi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtviurzrsb.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtchyvmnxh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtycbbaqyv.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtyksxqxre.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gtxjvbluux.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtfcsngtcq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtfztxvwhw.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtcsxmavsm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtrxalbvqn.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtovpacdyt.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtndcahzlq.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtokkhbxcs.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtosrxzywl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gtwsiapety.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtyugvebxy.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtuvaxfcov.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtrdwlntwp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtznejepgs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtmffqgcai.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtihuditjo.html


<!-- 参考信息 -->