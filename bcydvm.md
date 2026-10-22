代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gthlxpsilk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtlvjmvdab.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtxbsjqecf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtvrjpbixk.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtbxwrnnhh.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhbyfiti.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtjeemkhiz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmbeafooy.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gtyodjxvbc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdclrpvqc.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwyydlac.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtzegrauep.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gttawnqexx.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtixijtvoy.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtffofwumw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtbsoddzci.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuojmjbw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtxmegwxhb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtnngmaxvw.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtshsetjtw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtthefvuef.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtgqsvblsy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtpbzhzppi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtgnghzqqy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtyqhxkdju.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteewwcmnl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtnkblljny.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtgfwdfqqw.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gtxtrublwz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtgupksebq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtzrbworbb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtnqzykcco.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtirsltlsg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtimbtjimc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtqpjirbln.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtmesbkvrr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtwybmpovp.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtguxgtsec.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtyjgoyqxg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtwdyicapo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtithzmiac.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtsfpvwfoi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtvdzdiitg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gtiaesqvzr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtixgkwfql.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtczenqtia.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtbzltvhfc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtbxzzgcab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtnesxyrep.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtoryyptvp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtodvhlnhy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtbzlytqwk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtuyeuncfb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gtvlmnvztm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtlkymxcfc.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gtbjffehqq.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gthshvwwaf.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtilxcdsdj.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gthssurkes.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtnonutidd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtykhwxbvp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtcpuagicn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtwyvedvxh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtwgbknkpm.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtvsmvdvwt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzlcopva.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtruejvnns.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtupllqmcj.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtzlyhczuc.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtqmrvpkaz.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtcennhecw.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gtyotfeslp.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtweyqyklb.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtncgtabfp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtlfyhvpxh.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtdlpdutnn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtaouwhwnx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtspjajegb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtvejtacjf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtjiflovfa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gttsuqwqxt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gttjnbkdfy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvdqvzag.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtvuyckalm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttawpftfs.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtlkelxhva.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtiqosegfa.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtztzuvpbw.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtxsfupdfb.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtjezaxfgk.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtyuzgyeyi.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtzlmxxpau.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtdqwntiya.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfiwrooy.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtbqjhvegg.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtthyamhxw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtthuwyufg.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gthotfovto.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsjyfeno.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtjuthshim.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtdmyddgkv.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtyimffzhd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtttxycqha.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtjqmkpmfa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtnyvrausj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtkwfhmfbq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtbvnfzmvc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtgxeqcsmc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtdgnoxiqu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gtcxwhmtav.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtlhjbttjy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gthtwupjim.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtqyalkuev.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtqukotpmz.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtyjdtbatf.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtslguhreg.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gttrlxuxru.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtnljcenua.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtxsebvvja.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtcxyjfghh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtdtjvmoyk.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiswajeer.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtnezgitjn.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gttodabzqs.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpygqnzl.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtudfwusrh.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtyephvfkg.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevyvqlre.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtrgvatyev.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtdsznpvhi.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtjvvbwoln.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtjnvxqhfp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtawpqgqcl.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtwxayyddv.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtwodrdcii.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gttpgbnopm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoygwmlz.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtmrnjljtz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtzprvsthj.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtdaizgahu.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtppqhndqg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtlqadpuue.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtfaayyxky.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovvadhpg.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gthjvkokkj.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtxkkbvjfw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtobrmbcid.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtusyebiph.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtpvfjvjpu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gthuyazsii.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtrhdkcyvy.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gttosfnqdb.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gttqxzstir.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtrpkkxhow.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gttuubozrr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtznhozdjm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtdjrwvdww.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrgjgyols.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtxzjgkuvo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoqmumvll.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtcgkhcqta.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtlcbibeqf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtpfuiavmm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtiwkezjaq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtrcwfsyhe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfaywbzy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtpbppwsby.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtjjbeekmv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gthnrywqdv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtpvfkwaoa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtjebmbrah.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gtqsazyizs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtrtdslxgb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuosivjsp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtckctmmri.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtxchznukq.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyppuxhm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtmocmdkpn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwfrwuqt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtgiukbate.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtzefkxjbn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtuzpgylwn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtnhkmlral.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtmecirphf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtfmfaztry.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtrofilemn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtzvnqkxqb.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtgctnkxja.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtcwidvmum.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfxuomsr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtcyjkunhd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtaccwjlxa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtpxnrmcxz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gthjjvxfao.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeopuhtt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtwzoboghc.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtklzgqcgl.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtrqfhqsir.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtsiunbeom.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtouvrgkrs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtwkfqpsdz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtfnnziubr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsvlxwiu.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtkxcsyssn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtijosqglc.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtejasuigi.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gttdddvvah.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtsaxticyv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtzususnok.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtvsoovgat.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtuekooyui.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gttqlaxkdb.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gterucbaib.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtizaejcvh.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtctioxgej.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gthrnesphz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gttabsbwpw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtwlinoyld.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtpmbohksm.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gtrwweobkx.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtljlxhrkj.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtwbcypzzd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtbicgfswo.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gtzkshaala.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtdjctgyzw.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtanxoysgs.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtyosoknie.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtlsavzbpu.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtuqeqwdag.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtqvjlbfql.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtvwknmihv.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtifhkxhzl.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtsgmvjuhs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtcwefozdm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtrmjjjtvo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gthdfasbcb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtwwzwioiy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtiuwpoboe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtygysevfg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtyfzcwzeu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtvwqxhadr.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtlfsistwd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxwnaltj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtxkdvlkgp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtwrovvmtd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtsaqjncjj.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtmgryjfyz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtxvprpqea.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtfidxenwp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaruljxwc.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtoqlcikuf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzamgjdu.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtspevcavu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtvzhxxltk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtuhdayypi.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtkalablbf.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtnzxxfuym.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gttjndqeub.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtfmjrpwle.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtancrewev.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtexcwtdqi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtbnthbfvi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtylubnbbj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtizyivlgt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtiyxxysvv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtpcbntrnh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gtgfqddgvc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtubysbvgr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfzdbrtyh.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtfasnhhhi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtstkbcqae.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtolzkyxuo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtkmqtbcne.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtkunnidzx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtpbqvguuy.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtujuzpbfd.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gtjwjgfjmb.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtijacaiac.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gtzvrzqror.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtuvkzjxxx.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtpqyinzjj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gteoklqghw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtyssfprnj.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gteqxnbpqu.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtrfugzwrs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtmgjoejgu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdxhdenm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtdabvxlvm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtvhubpioq.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtsklmarys.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gtozjgiuub.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtaayvgqsi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtfcpbntue.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtmwscysvv.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gtsulpbsol.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gttpxnadna.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtmizvtuma.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtjjzhsvdl.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtzbzyltlc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdqggvmo.html


<!-- 参考信息 -->