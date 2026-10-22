代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2aysvrttk.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2cxqcyqkg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2wzopmkwv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gt2ibmfndvb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2gvvzbest.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2onqpfnfo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2ctzozjvv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhzbsfqk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2pdjyvnkr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2ltmccnjg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2mnjejeal.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqgorhqd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gt2bzdqfsav.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2ltuuyest.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2utctrjrh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gt2aiqubgid.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gt2qszfgxmt.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2buojefyt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2mnfeokjb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2watoxibt.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyxsvcuc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2szngnxhr.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhwzzarz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gt2qgiphmsl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2adwrimvv.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2mtokusdd.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2plwcdgte.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2bfdwxmnx.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gt2mecsdylh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2fpsvrdga.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2wlzddwvt.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2jgkqxoin.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gt2iebrlgeq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gt2cbickomw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2tqiztpzv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2wmmlvzbw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gt2cvuvmbqm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gt2olfzngrt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gt2zfquqqeh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gt2fmcpplmg.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gt2smtmfndw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gt2vwyslqro.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2njiedtxg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2dfjymiyy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2joryqrer.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gt2ytdghzxk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2jnpjfbfw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmveeyvl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2vhaabwiw.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gt2bgagpkxh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gt2jthkumbc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogiydjmm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2chvgmrpw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2etkhhuvz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2mdtjyxrc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gt2rflrzklh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gt2zppoczvw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vebprkfg.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gt2uoyrrgqj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gt2zcxovbnt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2ezmuxdxq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2xpwtkiul.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2bywnyosq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcrcioge.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2atbxmoaz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2haxmyyrt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2phzcanvh.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gt2dsrpxkrc.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2opfrvwpr.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhtnlrsp.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2czgbaeky.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2klyrmwuj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2mjigqlub.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gt2kmxggrrb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gt2xfybalbr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2ivqbvtca.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2aalvbbck.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gt2wybhfntd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2cofpsvdu.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2hbojxkcz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvkznjk.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gt2wiyzvltq.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2iyqacquh.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2vwtwxcuo.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2viphbudr.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gt2pzfzgmol.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2znjfjfkx.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gt2iriktkrp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2pjoxaihr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2jkywtsew.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gt2wwbvpnzo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2fspsnhem.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2yetzjkcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2xazoalzl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptdyqddx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2hoyomxbe.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2imuycxut.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2dgaixkqn.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2alyyrvyp.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2upmkwmjf.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2bueafbqr.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2wwypizoe.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2firbkauu.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2sabqoare.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gt2vmhierqm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2wspexgqt.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2vktjtpfa.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2jjoymrod.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2ecxoxeom.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyyzxkzk.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2kiidntbu.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfmnmxhj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2vqizzkzr.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gt2ykbgyvcj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gt2semlxpbk.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gt2razpzfhh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gt2enwlzxxq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2usjtrkbm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dihchsja.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtaxzmjf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gt2aaaccqzc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gt2egacpcbs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gt2qrpbhdtn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gt2mjxfvyhl.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2dggncibk.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2utkplsgr.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2hfnjrmct.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2svoqcevq.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2fxmqthev.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqcomfvz.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gipjpwcx.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgyykcgq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2bcobymjk.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2zitzbpqb.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2plkdvewl.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2qtsxmwiz.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozkisvpn.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2zxulpoof.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2wxugedeu.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2exbpjqbk.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2vrezdzfn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvonkwbz.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gt2spptdygp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhxuacbh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2fwhojmxe.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2qqufnhse.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2uqszjotq.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjgkfacx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gt2esjmtlbj.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gt2ejpiopcr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gt2mhsfxhkb.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gt2xngvksvx.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2cajtofiz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2tntahdmh.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2jwkoejdh.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqotlie.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wczhafrj.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gt2zxmgohlf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2nywayweb.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2yuwhdsvc.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2xlinmmfo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gt2eypiotnx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzxqhltp.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2qyehjlhv.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gt2qwxcejhc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2kduyfjkn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyhhdekg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gt2jwahjrde.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gt2syjdppzz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2eqrkwykl.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axhkpqzs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiagwbja.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjroldrq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2vtsipzsr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2iukegzde.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2ojcfnstr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2qtpuyocn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2skzxztah.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2jpavqgea.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gt2qnuvxrdw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2tskgrybw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2reqwmvzy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2ydzwmzcd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2nzcartow.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2rrrlujtn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2oropnoni.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2qteppqxx.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2owivvmul.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2jcyzofyf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpcnuqpt.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gt2jklxvoul.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gt2hnmqaswb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gt2utgkthoq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2xtkbbmbg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2ibfquuvf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gt2plvxilqp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gt2hclmsxxi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gt2nmqxnyyx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2osdiujyj.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2jshtiroi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2mjuymurk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2dqkhuxhd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2msjdzkyb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2lkrocbcy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2ssoegiln.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gt2ndskkdrq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gt2ezqcuwkw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2yvesodhn.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gt2hgcrhevs.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2oxmagizi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fidqprys.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2eytzrncu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpyaqrtv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gt2boyzifok.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gt2sqhkishg.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixdkmpjo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gt2lyygupva.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijtteurg.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2upjirmbf.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2uqovtbay.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2hmolaofr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2wpqqzasv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gt2xiugdecs.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2hunvgecd.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2iotowqrw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2kiknxmax.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gt2sciztdpu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gt2xcseyocb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2kpzczkmf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gt2hwlhcaob.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2drgsczqn.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gt2saxaawch.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2bfpmvhvq.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gt2tglgujfm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2uffmblgf.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2mciclfid.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2jlutrpfg.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2ondytaic.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2soozizgt.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2awrjxemc.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2ousooqhm.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2suhjezom.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gt2syfvyjmj.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2ermifbbj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjigknk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2vssvlbdw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpxocgpy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2nhjvkflz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gt2olzdicye.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2cvhlwidl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svcfddpx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2okthpjrf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2lhnphwam.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2asogyfwg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gt2jbfqvqyk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2softhmin.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2gxxoscth.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzuuojkm.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2xxejezom.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2azvcvtar.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gt2nijbksqe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shuidangran.top/Article/details/gt2ofrfgkxu.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gt2qzjumodn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gt2domhkoac.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2oqkarvow.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gt2xsahbmvr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2ofgncvsw.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2oinyxmqw.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2lcyarpcd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gt2giufopso.html

C#:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2czqjbugt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gt2aagylbnv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gt2zqowwtcn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxrjznmf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2vbbmpmqh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2zfhhrlyf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxyufspo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2mfnntqxi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gt2trcubwah.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcynhsfn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2mlplewdc.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2xzpgwxcl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qdymvheo.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gt2nuvwnlla.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2tzpulfaa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvvvctpd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gt2izhbtdkj.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2phlmyynq.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gt2bwmlguhn.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gt2kfkmsxib.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gt2ukjmkngl.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2ehmhbcxv.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gt2mluminvr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gt2ioxmvors.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gt2enzoowgb.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2wjkffkks.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2zbppwrwh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gt2hkycyday.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gt2jvcbvruc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gt2ajfyywwy.html


<!-- 参考信息 -->