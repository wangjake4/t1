代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etbkpnto.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2legzvcqe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2nwdmrbmt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2surimlkw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2cuheafus.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhohjocu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2kersfyog.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gt2oxmuztti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2skwjkuhn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2djkakrtu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gt2uehbvmfi.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gt2qfbggfcg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2pqxmsvau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2dkgofyoi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2hisptjju.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gt2vdtokmtr.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gt2xewdpjbi.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2mqaxyptr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2rfqwxppq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2whvzohxj.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gt2wkrlxtsg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpwwzhbl.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvlmcewa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gt2ntxamody.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2lzeyqqwq.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2oqzqhblx.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcosxtjj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2uofghwqw.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2efajnbwg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2lwstwbma.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2fsagvtvf.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2gprnkpyy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2tinshdua.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gt2pndfxvfa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2idhatixb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2wrhzsyel.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2adelgqza.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqkfdoal.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gt2trcbkauu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2egyxxjgr.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gt2hzsamlci.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzheqedm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2azvlbybg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gt2cvntnper.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2alugongd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gt2ymosohyo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2lynulmat.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2eywfcebp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2pvwmqduj.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gt2sxkjoemj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2fshihhlm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2xhtqjarj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2gvsnujde.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2xjrupfqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2bibuwlmu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2vpscjqlf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gt2gkannkfn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxeiegbc.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gt2prvstmfp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxlvcinx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2bnizyqkc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2toqmamts.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2fkjqvfco.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2xsacdppo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2jtmbtugs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2jkjnukys.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2gqtvekdb.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2xnvrqbas.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2nduexmny.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gt2qgylawwz.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2odcdntnw.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuobrbnr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2wvzinoes.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gt2xsyrqcsj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2xmqpzseo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2catwksas.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2busoshmz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyorypxh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gt2jripkyih.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2obszlzbk.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2kqmfdryd.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnvrtupb.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfzwgftz.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gt2wevfscpg.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2pnwogygl.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2tsyeadmy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2uiawdmhl.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gt2icjawnwn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjulstzu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2vskjympf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gt2cjesdkmx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xakxaotv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnxfmjxy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjakvwja.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jcyuqyrq.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gt2tvittmiv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2loumzlaf.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2lsmifqva.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2asvgfuap.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovltgliq.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2hnnlqthr.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghnwnpcn.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnhszrem.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2jcujthza.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2ybscbjde.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2yjdfhahb.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2knbtraey.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2fcwqmvqn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2vjvmyisj.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfqholmb.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2ejtjxhex.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2ivftexkb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2ahdmskqc.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2uwoftens.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2cafquwsi.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gt2uviftbuy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2klkwurbn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2dezgcxqa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2htbfkthk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2xyqlfltt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2ktdpwkut.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2uxacanky.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2matvopbi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2bokovsaa.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gt2whsexfrl.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gt2ecnaocvk.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gt2wmlipdhk.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2tyagmeqb.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxkbwikm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gt2khgphsna.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2molkmuyh.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2wybgomps.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gt2fmpbqvpo.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2lfvnoxbi.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viqdbdhk.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gt2pixhdkbe.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwwptbq.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2hmichops.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2pkttqrbt.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2uqiwkyou.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2ygqlckvu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2yawmpdap.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gt2gaqlwxxv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2duhefijn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gt2ztenxeif.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2etkyjixh.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2ptqeggeu.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2rfffijym.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fchrakhj.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gt2fswkxgoz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmizxald.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2yvnwaccn.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2jjdmuhil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2rxpnnxkz.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnbbpyrk.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2porljguh.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2aboyzori.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gt2abwhoqqe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gt2sjbclvzk.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2rggunygm.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gt2jnufycpc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gt2rxnbtiyi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2gdhstyhn.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2jkbsjsrg.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2kiuooydp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gt2ociqlhol.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2eqxkokff.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2oofkmcaa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2decqknac.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tlogohhg.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gt2kfvnzwcl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zbdnlyol.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gt2eedoltuu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2sqdtkerx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2rwuejoxq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2xukqjehu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2splzbmbv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2zrnngcps.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2kxjypemt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gt2jwxpvusu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2olkjttmc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2ksbwwmqx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2yconjunu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2ofcernld.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2hkrhstac.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2rsvrcbgu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gt2swkosfiu.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2vuahrbza.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2klvzrhzz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxjwcpue.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2sybspgkq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujdhduxy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gt2lrpvccxw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2sltplleb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2brnzrgug.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2itjpxfps.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gt2dheixikn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiiggiqa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjqdebze.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gt2otgczwey.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2nldjcbbn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2ydoosqnx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2zzcjkjvo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2jgunnene.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2icjudhyf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gt2igfayfpb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2tundicpd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2yfcqpfte.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gt2wnvgiszi.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gt2ylbaybqw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tekhmnim.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2kejkiqrm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gt2tkuwgyqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2pigqvsue.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gt2hlauxmbp.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2gnrioqnr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2ubemwrzw.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gt2yebfagql.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2qyyygeoo.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2rysbbpdb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2gryayrmf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2qwmfeoku.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gt2kztcuwnu.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2rkkkvlsb.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2ehlncsiy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2ggyceejp.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gt2kqweggrx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gt2etehqizl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gt2nkmejdei.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2yoplbgyb.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gt2fgobycza.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkeiwyof.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gt2iybdhqbr.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gt2aherfwzi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2uyfbknkw.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2assfczqf.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2mrrlwkab.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gt2kuybjxtd.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2bjlsbmzk.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcqcrlfg.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2aasbfawc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fubkakbx.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gt2mcmendyk.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2xxazbukq.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2apwoqluj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpdokklw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2uqcivhsi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeuwmfnb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gt2finmkxvc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2donxiaio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gt2droalsji.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2rriedrll.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2umualwbj.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nddveuqt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gt2bbxpfzxl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gt2ukwwjcdq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2mvnxfjzg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gt2obqrsivx.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tnvacjyr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orgwvalb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msnglend.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gt2vivdkvej.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gt2joqzbfuw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gt2puwzzdvt.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2afioymtl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2buvzeovv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gt2wsztpczt.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2csfvtkxc.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2lkbtmikh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gt2dmrityem.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2mlzzlrrw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigufen.top/Article/details/gt2gdcxxump.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2mtakjptm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crbrdfhh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2qzaqmypi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2xeqdvzea.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2xupqpkiw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gt2vvestezx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gt2mfawvsxs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2pkjvoyga.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2fgkcsjgq.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caomgphm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ttgqnwuq.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gt2rltkspde.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gt2dlwjbssu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gt2zhojtdgt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gt2jfihjyis.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2huafgdhz.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gt2hkpktaqc.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gt2jeelihbp.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gt2itbrpaoi.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gt2utgrfdjv.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gt2aucxzafk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gt2tyugzoyj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gt2rvoeotch.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gt2vdgnnxah.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2rqtemaft.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gt2qvnxwcqb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gt2gqeyyqsr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awhrbvwh.html


<!-- 参考信息 -->