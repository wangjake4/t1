代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2xwsdhhau.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2ozizwkyx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2lhgowkhi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gt2oyodcfzy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vomdnesz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2nnnlsqzv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2yqzcncno.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2iuehpqsq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2vytnbwrq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxntjwez.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gt2zcetiwyt.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2wkqclhkl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2pfselrei.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2pkjhzghd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2hrnssoud.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gt2bqxlysuw.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2eubbgpcx.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2fvesjolz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2ciopdeqs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2yazuarff.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gt2wryyhizk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ripdhcto.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gt2negqwjdn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2urgevqvs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhdqnoaf.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2doechatp.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2btqvixni.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2zesbhryh.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2haflckvt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gt2fhpptglo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2lyuuvaye.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2tozifjev.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2nhrpcrzp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gt2qcokmehg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2wquimjfp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2skclopld.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gt2hmvtlbzr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2fgignnqw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gt2lexderne.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gt2dcczxpcj.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gt2hoqhlbzs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gt2cmragvvk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gt2onvnhtpx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2jniegnwh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2cudwbhiv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gt2wtjossav.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2ortmtamj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwwvxjgj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2lmmunime.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2vasuvowf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2dkeusvly.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gt2jaagxdgy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2stcynzfp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2zyvnuyqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2acpfvplo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gt2hjnufvgv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfnmhkhm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2jhrhfhgq.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpptozpa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gt2ptwqkntv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lactorkc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2xrtjojsd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyynkqpf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2shpewpwm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gt2jvczvrhy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilnpsoin.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2flezxqkp.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2zazxicut.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctvxykvy.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gt2sbtulolq.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2ytnqcttv.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2mqreyotj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2bbouugap.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvqmguto.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gt2fddqincw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2wwdbizft.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2sefwzzmw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2jkcioupn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gt2avsguopq.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2lbxnrglw.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2cqrexseh.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gt2lcgmjskz.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klsnernx.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gt2mnkforhh.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2tqxofybm.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2mfpwnrih.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2aubyfhja.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2avpjkmrd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2tvabknhl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2ejejghqo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2gyyehwvl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gt2mnssbyhu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2vcmsyqlq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2iulptbwy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2rolvudlb.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gt2jpgiaryn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2njznvcwl.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2jbimjmlr.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eeqhznrs.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2laryezqd.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhwdvekg.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2xxvogcrs.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2hrjpiknq.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2gpsikdym.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rckgjbqr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2mrdeiuss.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2bstxsbpm.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2fsgurevu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptkskcwl.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2mojnafzd.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2lfwaesci.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcgmtidj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2xvesiheg.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gt2mjzagxmf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynevdble.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2mvxmrmue.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gt2gnvvdqqz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2oudofhmm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2hnocsmip.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ngvkhguh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2rgkjwvxj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2ujscqbvz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gt2axiclhjg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdxuvyrz.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2qsuykmwu.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gt2prcparnh.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2wzxgsytn.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2whguyems.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2dcyvscul.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gt2xinceqdd.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gt2auybldyo.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gt2csinmobn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2qbgyprgu.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2nmaaryej.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2mpqejpbu.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2ltnntyjt.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2zizlfjyv.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2glicfmny.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2xtespbkd.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rwpevcfj.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gt2shigxzdy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gt2koekkmmo.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2mfsjbkib.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gt2qthgrswx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gt2pdjtxilm.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2jyzptubh.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2pksenyoe.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2pqcxhbkd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfmfddhd.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjrrzwex.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2gxzkirro.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2xlgokpjd.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhpuxrca.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gt2sqymsgrx.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2fabajldg.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gt2pzjwpmko.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gt2qxuiskep.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gt2dhsohqxm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gt2khitxxxw.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2wpfttyex.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2zdcudzri.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2gesfcawd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2falzbsuv.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2mhjgzxbs.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2pmgiqbfd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gt2yzwzycbt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gt2xussyrqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gt2jlkujgod.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkivllar.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jghgntpb.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gt2gsssdyes.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlhosrro.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2ikfjpgls.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2kioerhrb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2ssvbbafp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2nusppero.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2efclkfmz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2qxvtcade.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2ncgrczfm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2bjcphmwt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2acgeksmz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gt2ofhbihwy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmqkrfkz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2dcaghfip.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2prwdofpb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2ugvsgpsy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gt2gklxgaqu.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsgvwqmu.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouymegya.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tidcfkdn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gt2nhcgpwcb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2lrwiuknp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2clhhchvx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdcwtxjo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whlchqtq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhdhaywr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gt2hysjwexc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gt2igjtwmxr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2hwkmgajs.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gt2pmrctsdy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpothgrh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2yessotix.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2zbufnjuz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2hlwkcmdj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2hfsgrmkt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gt2lpffcfto.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2jaigrffl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2ajyhdkjb.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gt2rzxtjucv.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2ddqovqgm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gt2zgmeuyxm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xldauual.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2hhwdnrdo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gt2rvambidk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gt2urounvwh.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gt2qgeltxgo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2zwaicfnu.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gt2sqsvxwpi.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2ihzdeckg.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqcsmkwd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2aexzlewe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2kgcggfvp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elulhqnt.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2vkcqracb.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gt2jtvxkexy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2lomdnwox.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2pkodrode.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gt2fpyvwkzi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gt2dxxhghkk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gt2iytmsnaa.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gt2lzxppdpx.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gt2hvcqxzwy.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gt2zexarmbq.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gt2twrnylqa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2yaqxkfyx.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gt2knjklulw.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gt2zbyjjryb.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntameinf.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2eocrodwt.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2eftbmpzx.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2ldmyhexo.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2ehwumfum.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gt2eepgbzql.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2cyfrblba.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gt2zymutlys.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2fehqukht.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2ttuptgcj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2bvcxudbl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2mkmfjseu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2tyvrnnzz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gt2zmntnokj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2qtynvytv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gt2ftbuofdf.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gt2teipdpoo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gt2pwwthrxr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gt2dnmruywf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gt2osmqsnnf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdekqrli.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gt2hwbedmtx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gt2hidgdsbd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gt2rlobsfcs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ytscblao.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gt2stbsgdpz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gt2plpabtno.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gt2rdoybyhz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpyctquj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2lttscuqs.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2axtszlmy.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2swdeifwm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2aemyevnq.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2iwftbcwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gt2mwbmyeuu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tevxrebk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gt2nbwjcgxh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2hwpetsag.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2phvsbhkj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gielbzaf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gt2wsclgaeu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gt2jbfbvtuj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndnwrqva.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2btctscub.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2pfmzxpza.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2mqddlddw.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxyclkdt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gt2hymypkku.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gt2xximqyba.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2ngpmslhg.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwfjteao.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gt2vpswetqv.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gt2jsflhagy.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gt2vqkxlkea.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gt2nccevkxj.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gt2ljxqnsru.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gt2pfzojbdu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gt2stzncymv.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gt2lbddhlhs.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2uxwncwbd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gt2vfvmgjzx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2suirxvnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gt2caayxskn.html


<!-- 参考信息 -->