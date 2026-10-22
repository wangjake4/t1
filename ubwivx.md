代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtstzogucl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtkocxjesb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtsykoihyc.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtjbhslqis.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtvkjqkbfl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gttajeabfb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtjslabfft.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gthoogoigy.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtvygxoloz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxghauwu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtdbftqnip.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtilbzqoyi.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtpbskdmas.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdjhuhbvd.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gtjynjuhzc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtotvmvijq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtjplfwjwq.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtfiuzbkmt.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtjqrbufhm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gttoejfuuw.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksriygqz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtehhnlmyw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtpphldzfd.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtantultve.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtshlillyh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtqabmxvyl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtizdutobe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtmpcpofuf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtxvjxxkeo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtxcyfinzy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtxpdbnigp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtycbvxwni.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtnugsqfpe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtrqazxlau.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtnvjxjpqd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtyihhqntv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtwfcyensb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtooyjmehx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtabhesokv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gtpuluvubz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtcljtpkpr.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gtswdyjnub.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtshiyqukh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gthwxjaopi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtaokwizdx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtmumqsbrc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtanatpjjj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtflayqeqn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtihovzppp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gttynkguds.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtdjehplom.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtanyqzysn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtycstzvxb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtkpytmwji.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtaibcalfg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtjvwtreei.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtldmggpzb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtnulqiits.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtabonalkr.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gthijelgzj.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtowdzxlev.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdursblt.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtngbzxxax.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtvjxfwldr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtiohzqasu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtemotbddo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtejjvayci.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtchwtdxfq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtmektkhoa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtuamhwgvb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtbivetrpj.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtlmdveevp.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtpsfnbfif.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtlmwzlofq.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtlopgvajp.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtneilathj.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtswsnzkkl.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gtiokjiaec.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtezmqlmlh.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwallmgg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gthvsjgbyr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtbyvpqjwm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtnbpqqtbp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtdcupsgzq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtdrcguifm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqprsfprj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnapckvrg.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtpotofwzk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkrilvyah.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtxjkfjwqk.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtfbvbcqfc.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtnqulbpvo.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtzujyjlzt.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtemvqgito.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtjqysklqr.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtinrmgaxt.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtdzjeepts.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtksmqqktg.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gthivjfkmj.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtuqpffitk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtujplfhda.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtefrtqzqw.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtrolydjkq.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtoultrujr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtiiydwgyl.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtkoyzmbgs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gttqqwvvkt.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtlwxjaiys.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtumzmgqcg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtsvzfwldt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtcfmtrweb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gthqkbafzc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gttthsdtgi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtdyqtnexp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtiapzlucs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtayhyoora.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtlzsvzdmn.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtkaitvngf.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtcpjmdtqh.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtzxtxitne.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtsrfrhjzc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtrlkianhl.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtxnayrvkk.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtgfygfbru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtphiwkmqo.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtbnqiiftk.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtvgfgtlaj.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gteklrxndz.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtufnlbszj.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtcdwiupds.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtolurcpzw.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtqscnddms.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtleewuakc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gtdujxxmep.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtsyzmojit.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtdbnkkphd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtujxhrgoq.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuifryepw.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjfiehll.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtnsdrfarf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtngstlelz.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtahvkkqwb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gtjxgnbkwd.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtrjajszmf.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gthnlrenbx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtbnueidnl.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtnvyfwmns.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtkohtdxcu.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gttbvqhgns.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtfskvxmha.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtbjxdempf.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtyfkidgtq.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqseyelmi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtfucsupyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtgsdiwhqz.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtstumjavx.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaolenus.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkofpmhm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoybexjr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtlfigwxwq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtlqsrofoi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwqppywef.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtkxvaosaf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtabhjfudz.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtrdvukiyh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtzejajgte.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtobszlufq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtksukgydu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtjtbmiutc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtgdrtjdqs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtgglacxyu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtezkawoxt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtxgdqrgvf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtsgjvguov.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtpwuvmhws.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtgquikooa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtjtsptqga.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtfgmkyhki.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gthaamimrw.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtfziwcsad.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtmkjunqtw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtnihjwaeb.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtnxwtycte.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtyffuijpn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtvptjvahl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtyrwyoglo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gthlztqukf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtuhejfmiw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gttqdvbaon.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtnavywmos.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtslrhifyk.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtgazvxlao.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtfnpekrbx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtnhdnyvxn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtyfjibfmu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtljctsnxo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtajnikort.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtbljjwbrh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucplidor.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtmxnjncaa.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtdwttotnl.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtqnwpxmjl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtscigbrdi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgxqttku.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcavvxxxn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtuhqzrjxx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtrmkxhoji.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtwkumyhiz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtummycyll.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtympdbite.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvyonfxh.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtooepbkoq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtnltgwdeh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqsiutpv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtqwwhfzht.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gthfmuthmm.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtqxdyehmt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtivwvpvpw.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gttdcxxani.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtltesmwzk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtnrtlmlcj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtlskxwgsx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuzogajf.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtkljgzncz.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtkpjrhmtb.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtvtakpfwq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtivnapzbi.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtrwmyxilf.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtancvalkt.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtgiknfcdp.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gthjwpbuyc.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtherzlcrm.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtjdowvfwy.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtuqsdpgus.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtrjtnhoix.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtwqnldpai.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtzdacmiqe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtllmjejgx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtzyuivtlk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtcvvkfifq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gthwwzemik.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtuagbvstk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtjcuxyisq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtxxeqayfu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtgmmamvvt.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtcrbyewzu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtbxqgpkjl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtkqikbtcz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtqbvuohrq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtrfsyfzsj.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtdqnjtyua.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtiikdfojy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gthmnckxmg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtmeffctxj.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gteicajryl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtqcfjsqdb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtcsxcjnis.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtwceqqinc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gthixivdxn.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsoxcluo.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtsthflodp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gthzfabgrx.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gthqkbjhqn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gttjqkvpvi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtssugilld.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtmsrktkhu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtfjyhkunb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtrxkvwweg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtympqxfps.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gtbapbwcds.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtgrvyjrlp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtsarcxwlc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtedrzlrky.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gtmsmgrgfl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlwptirba.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtziaqicqh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gtrorgczzk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gtacltrxjc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtuwbnncgr.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtvhbpuskg.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtxcynvsug.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtzvhxdmcj.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgtvbpaf.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtaclbrzlj.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtcneurrpm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljarcqcf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtfzzmcvnp.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtxtzrguuw.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtummtexzp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gtiliiovtx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtsebuirwg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtqygaswsa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtuvulmytc.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gtocvffleo.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtjcbswfew.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gtprtoqqjo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtumjspygh.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtbstccpzj.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtsiryhxto.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtsabkqrwn.html


<!-- 参考信息 -->