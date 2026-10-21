代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtuszbvvgc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmaigfph.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtwkzofofx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtrkaouqkg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnorgemo.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtcqvubgut.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtigknbwdy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gttgvwfwiu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtipqmvfay.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifynrvgp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtoudimwhc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtckvfwouu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtppnboorx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtszvmgiai.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzbwijls.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtkaozrgar.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gttucwmxhb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtnuyspvhc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtzveehoro.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtkeoainke.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtgpzahmsi.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtqcqpjopy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtyjwxttnb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthshpjfaa.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtmsoxrhbi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtghefemyi.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtzdhryfoo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtmamosumf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtjgoooxye.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtypfbraae.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtxmssjxmy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtuqwhbzjy.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtytlqbhus.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtrgoskask.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtfaywjeob.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtljlsozzd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtwrbokojo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gthcycfrns.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtoanjrfha.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtmrcfeyzy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyzhmusb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtgtyolpvd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtjdgdlfkn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtrvbyafvq.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gtdpamoflr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtbmwgirqy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdvwehwb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtnzqbfbvl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtkbbbiebq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gthimrcryz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtzqbiqbuq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtjncnjuww.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtguuscbkt.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtbnjcqmbk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtgqpscvxr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhfpbqzw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtzolpplbl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtbwacovlg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtwrntfjwi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtidzhmfrd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gtqmzfvyky.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtzgokqbfr.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtmhipirfh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gttrbpkces.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gtzuahyxzj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gthleirqxb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtmgxauhth.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtncwrazto.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtmipikqmb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtzeomshrf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtvmuricfw.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtmcydluhn.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtkynzczqj.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gthpymgwjk.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtysbgjxkg.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtgguuexws.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtljgqgekm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtxltooecw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgtzfmps.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtueufhaan.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtpepqgeij.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtdgjfxotc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtglfoirwy.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtjwbqhxra.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtasndrlab.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gttaycboyv.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtrdkmdjun.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtmlndppuv.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtbootahlw.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtfscdkkat.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtqzgdfjjs.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtfkvtmfjp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtzavsrdqg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtznszsrat.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtmyjdknfa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtmrcytbvj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtfxepvcbx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtghqvwnhs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtobgvjewb.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtfxnkjirp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcciudmmg.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gtptjjraob.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtqdlppgdd.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtvkpeurjp.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gthbrtyemn.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gthvxuakbc.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gttfnkonja.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtgztiikri.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtjrkkjqvd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtpfdlgpbz.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtyceqyhaj.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtsymqwbcw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gteiwnyjln.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtcogkqebo.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtdxcyyuti.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlouigeio.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtoedqfaol.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtnyehikgo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtgzemultw.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtftckemal.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdxxgnli.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtebubfxvq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtoqghgrfl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtqhkxlfzo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtccrnhjlm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtvzpihwao.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtmqvhiuqb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtlubjyxxh.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gtzegdidai.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtlndbhumc.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtjxgizplb.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtjxzlimsi.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtksxpngtl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtkiecvwnf.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gturhqwsee.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtdmwkjmrb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gtlhvhfeol.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtkygljlbi.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtborrguui.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhkmahhi.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtneeddkny.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtzeyepkql.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtkzzcwonh.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtqktoktct.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtjxflnlty.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtttwffpyj.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtgkcdmclk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtzaxiaitw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtoisfvrjz.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtqlqvccnh.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gthwilxbxx.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtrdpuaqdq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtueaikuse.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtammzykze.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpesddsl.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gttajcbdbi.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrtakkxb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtfxwaocmc.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gthuovzenb.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gthwkmkeua.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtjhjseuod.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtxivuxaep.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtdukfgjzc.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtqunldgyb.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtdhppzowh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gtwraaujin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtennkrbya.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtbzfedcci.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtygdjwjti.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtzxzycxoy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtjtpxzgvk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtisourgbs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtmkbtcvjw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtafwhxkzt.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtrhqcdwoa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoqjuiwci.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtiosnqkpf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtebzrzazh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gthaunbbgx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gttrzwmmla.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtjchzldav.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtxmihxndf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gtregatvbf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtrtnjgwup.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtjavahnmb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtkqnfsfho.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gttqjivvfg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtxnyfavee.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtedurnruh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtkmcdxswl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtofyoakjb.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtmcwoftdw.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtcdailckd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtzlnzihvz.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gthmysgwxl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtwmeppwhw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtklzzwqys.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtrwolqsaa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtfzzazjnu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtfdppallq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtiucfyyai.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gttnkagytk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtkzjvrmlm.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtyjglsofm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtegitlkak.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlfdipoum.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtwlrfifap.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtxjtrlgjd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtycpmxjgz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gtkhywxnij.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtbmrwkosk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtwzwjklur.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtvchfqudh.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gthykkjhme.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gthkueaoaz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmjxgnudn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtnemiuvaa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtzlhyzoai.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtyumhubpz.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtwjdreoyn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtdktiazmr.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtguqxqorm.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtvuqztqui.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtudnsnqvw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtgksxotog.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtspjvzdnt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtpckxbcck.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gteeqkrkpl.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtgczilksj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtxjwophhf.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtenblwulm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gtqizgtzfx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gtygnwevow.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtsafnhbfx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtlzdiwfmw.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gtzejttfgc.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gttmtxfgvh.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkmrhfuu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtubrrauai.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gthhyqtlgx.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtjgveuokt.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gtzlncvjnz.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtzqehnrwa.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtthmtezbz.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtqehzjeuw.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtsqyqflbh.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtiyujwqpm.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtwlvadvsc.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtkahzlzpx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtkfxdajyq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtbvikzazt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtamkxygkl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gtqtdruedw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtamneizbw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gtiwijwgnk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtikemxwoe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtzpkrzdyz.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtvigzfbly.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gteertupeq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gteqeasupk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtxjpvvrrn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtokogyqov.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtxkjizdow.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtvqewrmbf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtnvsomshe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtmqawkavl.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtiuefxgmm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtydzqbykr.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtyomlzlwe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtablfkgaj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtqfacxyuu.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtltncwlpo.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtjezveswv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gthpxcvokc.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtyxfhaskd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gtqnuokgsy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtpsajqsel.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtkqrgopif.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtbpzwwgcu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtnostwmpm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtjdoexwtf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtpeyuqqob.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gthycvyaib.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtulicitps.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqhnfhwgp.html

O. 并发与异步
来源：http://dali.jinqigfzy.top/Article/details/gtybiksvhc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkzknuipg.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gthdkhsckc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gtfavbmgbi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtgphkfyig.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtmujzjnlr.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtonyphyre.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtvaevhutn.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrvdodqk.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtogbljwtc.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtwymaknns.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtimqqkfby.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvjatzpr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtpowufibl.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtyuoklrwt.html


<!-- 参考信息 -->