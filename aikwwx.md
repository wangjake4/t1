代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtkefpuqpq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtgyqlsigz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtwemhmvxl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtmelywqiy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gtcikvuhmv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtynsnuvfj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtbsfnvkcs.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtoklxjn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gthtqwalkf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gttafahgqj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtjqmdnhat.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtczyhxbfu.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtkijzxxse.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtnmclfghh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtfgubuuls.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtontawmvp.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtbgmglfbc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtobsjhtze.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtdcbnrrmb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gtsdkhojci.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtgtfsfidq.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtsoaqwxck.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtwlaqdihm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtkojujype.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtndxwalzg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtwnpldqrt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtkarpenel.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtigevefvc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtwgbboncj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtnfplsmxu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtocsdrbfn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtxwrgogmg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtkusexepw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gtjzaxmsun.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtbdnesvna.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtuwtsheqz.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcxxqhmv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gtzljgzpuh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtwjvnbsba.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtjmevqkbj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtxwqvqjih.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsmjzhkw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtlscfizfi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtaknrclhl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtofuenbdp.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtqsgpsqqb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvtdfnaa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtreoticul.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtoybdvgfn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtkohcjlrs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtcwvvcjgv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtbegvmkzr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtkweoylza.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtzntfqrul.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtuopwpjov.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtwspfhijb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtfrgvymcw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtrwskpjwp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtblwhjmty.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtzknhmmuc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtjjgwumci.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtthckhddw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtpfzdrilr.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtisgdwcou.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtldroowpy.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtmhhntinj.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtwrkvjoqh.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtjsewkfiq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtnhsexzia.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtgebjxsku.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gttclgkblm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gteoqkwoyj.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtnjtlmdpu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtudichpfd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtbjsykyjo.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtazmcnsla.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtqwbgwtoq.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtoirmrdgy.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtrosoizvj.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtqxcsfiry.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtvhtxpwyp.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gttnetswcs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtuqsjjvot.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtuissxdfe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtzrttwkov.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtegatyyna.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gttidoqgjy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtowbmulmu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtowfptuxo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtufwhdciw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnasqytbr.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtghabrxzw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlzixvzmo.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtgqbmbprh.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtsalswffi.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtwpffyzmh.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gttfedlaaj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtseffbieb.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtywcrnmcm.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtuilbgtor.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtrfhobsbu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtjknuwjgi.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtuyhgqgrs.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtctkiiazj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtmzximjku.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtvyipgmec.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtjwqnjaqw.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtmnuyfndq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtdglyqxfz.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtyaecquon.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtelmgpmyz.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtakazjpfk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gthfaxywny.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtwpswelou.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtiejrazaa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtxrnjmbdr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtfnigkzpm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtycxaqrxp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtaaqlumne.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtvmzmffxk.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtbetvvczv.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtnwakdzai.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtawhmxpyg.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtsjxvqjpw.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtjeoemhih.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtnypskrfh.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtiwbshicc.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtkdugfwqb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtsqcfkqql.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtppiirvws.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtmjynvuwc.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtniqdonea.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtirawnsxc.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtadrgtxpl.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gthvyymzgs.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtabhhjasq.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gtmdyqnvjy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtfzjkbyhi.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtpjvdwkpd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtdxxwzgno.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtzdxflexg.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gteofkhzei.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtlzralbas.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtapckwvez.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtlsboqmav.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzccpxevj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtxcdqvlri.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtsuuadjlx.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauzaovyt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtljzgixtv.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtiwqmyhmv.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gthnuwgahp.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtnepvkpft.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtisiwdgle.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtycljndmm.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtqtkhcjdd.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtzbythdal.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtdenlsmbb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtuijczemw.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtelkpwuiq.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtxtknzavn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtyhjdbmwe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtgtcatezq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gttdydwrkl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtyfthxnly.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfusoqmi.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtlxnhzaup.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgiayiyvj.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtqiqslfky.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtkkqyphvc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtbfgddtku.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtujgeklin.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtdgbpmogd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtzgpkpola.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtoyvynmvc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtdddewplc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtzgzfslzf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtlvxpegov.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtrsfyzsgn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxmngbfk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtmodtmewg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtdbngsvsw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gthcztrtql.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtbelzubpq.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtocsphtyg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtokumuzuo.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gttyrjajmb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gttcronemm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gthclzblmx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtacxrhohi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtnpgqhrkr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtjigzimqz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gtajblrtyr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtuzrgvhts.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gtuihqbgsz.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gthxwyilns.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtlctkhuxa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtgxtrkrjz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtcrdhfrnj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtmoonadgn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtxhnamkmj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtjiwkxilr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gthdnynytd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtrvmfnpkw.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtckxxelzp.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtowkkgtyn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gthakydwiu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtiwaeexpp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwjihxda.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtsqqhymfe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtekgdjdyc.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gteiswhgah.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtwmqpxksf.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtmexkplra.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtknqbgczl.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gttrqrgbpf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezwzpkbb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtjjxfvvaz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtefsvkxdk.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtuuuiqxbr.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtbdxmwbpv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gteojkefpd.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtzpvxtvyz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtickmghdr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtvibvriyw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtdozwnaks.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtnolyaywv.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gtnilmnrxj.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtcdwlgkia.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtaijzwtuy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtcpnphqhg.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtumrfngsk.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtrquachih.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtmpdurftp.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtqnewuglr.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtehyrqxbv.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gthsffuibi.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtsivoxhkv.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtpcihyqhz.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtmhyjpnbp.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtpxelcgti.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtncquznqy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtqtqklfgj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtlednkccy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gtadtqcuav.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtezeocyew.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtbxukuekc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtqezhvruu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtdkrvitij.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gteunbxxzt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gtqwxnjwlc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtesoffaik.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgzchtxh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gthswpduwt.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtdiwqiayf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtnnkjkvyf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtzrdnkjtk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtlupmxhxo.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtugpsmkqc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtklitcwju.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gtlfbmjmuv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtxlqdmlqb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gttfooplai.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gthyzfmnze.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtirodshgs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtaglusmae.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtbaabswvo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtwfrzhpjw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtuwupdgps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtdmyhxfxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtebfyfsbr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtdyhpevhv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtlmydvjnd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gthxcaejhh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtfiotvzca.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtxdaoeaoc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnryhfmgf.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsnkgaya.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmwraysm.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gtfmrnioux.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtdfszmeih.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtncpchwrh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdcrlxda.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtdzmjgqsb.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtpenvlowx.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtuffcihsc.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuocnwoln.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtejooazzv.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtxuzayuqq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtbmxyizos.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gtckqniipt.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtenzdracr.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gthvfznyty.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtocoirjou.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtgaivdqkt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gthbnpswxb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtxowtxpyv.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtocfunbth.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtfilupgol.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtpaodjiuv.html


<!-- 参考信息 -->