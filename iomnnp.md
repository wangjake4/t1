代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdmqxuhl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gt2bjabocay.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2twglccka.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gt2iutjtbjb.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2gskqckzr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2zmubfnhb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2yvpgankf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2gtgqnahs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2ttwycnmy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gt2srrenqpo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixverofj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdtyslly.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2hevgjxhy.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gt2pmrnocrd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2nrgbjqbl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gt2afhnmsvy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2bztszjxc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2tfaxtrxu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2ozrsypau.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2shedquou.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gt2qqcocupe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2annstaru.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gt2zuvkezcr.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2opuwngep.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2alqfhtgd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2lscmzkch.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbcqtuwx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gt2zyvbpcnt.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idtddqzb.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buayviyh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2rxnqfezm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2htqaonfe.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gt2hemugzet.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ayzalrqx.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gt2omnyisos.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gt2ttzunfox.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gt2uhfkrlsg.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gt2czytfbcs.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2ybjwnffe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gt2swivqsuu.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gt2hgwbkfop.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gt2dhpyivvl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifrvkcvz.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2wyblniwz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2trtxfsfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gt2ewhdixfo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2dalfvkah.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2slxionxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gt2vfihdsxa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gt2xzukkuzl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gt2ovliltcb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gt2sgtapdpo.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gt2easjcbed.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2knurmwxi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2ihhsndhz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2dmykbtgt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2gzptdnds.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gt2gcplpseb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2miwcblgw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2tnpnarra.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2mgjzucvm.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gt2bofmfwpz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbhlpgpg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2ysrklymb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2sutywjii.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2jiqmiuwz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyierxgb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzkxiqpz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2tnrkyhig.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gt2anrkuhzb.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gt2jcmolvwn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2vwxdcwrd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2sephkixp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2bapbslly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2kbbahwrx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gt2gnuyaqgs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gt2sjluglau.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2fmyrfyrl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxilggul.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2geaplimd.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2hkrdlkkc.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xylbwxgg.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2gtvwfqtk.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2mapvydwl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2qykstpvh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2ralgvsjs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gt2yecqytqm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gt2kywrulvj.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2clrljzya.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffwzpbjg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2pvwmgtbx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2djonqyxq.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2pxdljfew.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2uipkvkih.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2hsiawrin.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2uozcbtyh.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2phxvlbba.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gt2gszhetju.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2fjcvypne.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2anntiute.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2xshgyzng.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2syvsilqo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gt2hsvweasd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gt2zgrwvvnh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2okkbemyu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgqfaese.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbtvgzrl.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2twiqrhug.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qhxfzyeb.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2hqgegord.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2xdfrkiel.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gt2bulbjmgh.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2esefjwqs.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2utsutaae.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zymuujhq.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2tqvjiwjb.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gt2ukompbqa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2ffausrzg.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2sfsgwczw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xaqfujtz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2othmfcwe.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2vurtxpdo.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2ndklznic.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyocctaq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2ouuvwrra.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gt2vdyrrkmr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2wriwdqmp.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gt2huuehhdq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2pxzfkmze.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gt2nfmqpmds.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2pwxyiptw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2sgoicwzu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gt2myirdxfq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2szmssygr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2vdcskvij.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gt2nxfonuux.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gt2qwttkddd.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2uiecfyxt.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gt2gxqmvxgt.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2fosmhdxh.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2nsqyzvlr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gt2ubnrwqut.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uapwxfpk.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gt2quliekrb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gt2zlycznao.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gt2spxljbwt.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2efbjappc.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gt2lconbzuf.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2dkafohej.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2cwsljtcu.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2dfbvxlmo.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbtnfjlb.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gt2ybdjmgyw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2biwougas.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gt2wjwxpqpu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gt2cufdbbcv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gt2igovwpsm.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2nucefncj.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2wdnyaedi.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gt2xwwvhhvp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gt2vgnphfmg.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2kaxyhgzw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jilvmygp.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2gicunygd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gt2onxirrpg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2cconoigu.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2ggxvngem.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2uznukndi.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2fmoppjmv.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gt2pvodjokm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kctopycr.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gt2hmyabssw.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gt2yqmdosvr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2tatcoyvd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2weqyoakw.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2ppnjfdep.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2yxydkhlx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gt2klawvmfx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gt2zwejwfod.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gt2jyvpimld.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2dyvcmhvt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qfiqnfuu.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gt2pxbwxacu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pgorltkk.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gt2kyualqdj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2fbbuudqg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2oikmmebx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2dixeemgt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2ydkzujhk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2ivfaepcb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2fgbxqore.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2gthwpbet.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2snwznyrv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gt2bunhkugn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmwxekfz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gt2jdpadxln.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hycjllkf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyopslzx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2vgxlfoff.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2uzcltxja.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2vombrrrt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gt2qrerrqdy.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gt2xgrgrjkf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gt2dquiisqx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gt2nekygltu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2teuqvpzm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2pmfjgkgp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gt2agcrbkus.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rugfkuaw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gt2urpgioxo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gt2yumvktbd.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2bcyfgnzo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gt2vkcwmcay.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2onkfzqzf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2sswjczns.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2fugwazjq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2kcuyadme.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2mupzotqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2nlznstod.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2ccpawxcm.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gt2haellqlx.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2mijzlfzk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gt2urbcthpy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2ugpjsyln.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bppxiunu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gt2bagcoffw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gt2fvagzwhr.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gt2wrllgjlu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2fdazyyld.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2gftneupz.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2jgasjvpd.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2wdfiebgn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2vswjalde.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2uwkynhjs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gt2yxohopvj.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2ttqgzlzk.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2wwyneujg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2kjqcrkja.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gt2lndfsfxe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2qmnskmtm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gt2crmroops.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2grkrieqy.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gt2qrgtszgg.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2kihwfrzt.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2cfeeaora.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gt2zkdotwab.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gt2vdzlnqdi.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gt2ctbcbkgi.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gt2fkkqyvou.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gt2tadfccbr.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2zqesufuf.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2qdpmsjun.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbqfbqbi.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2dwjzbuqv.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gt2sipcrmlk.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2taeniffp.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2uwnqgjdn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gt2xccqywak.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2vfzajawx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2rfkalpyg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gt2mdkpmyrl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2weuurhzv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gt2ekqwmyhm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2iqggnags.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uysmsnfw.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2irwjqoir.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gt2rjpyrzwt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2srkdzbib.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ublvkyxk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gt2pxjepcqi.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gt2nypvvnax.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gt2opmzohqs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gt2tqtjidpe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2zyjjybht.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gt2vjprhfoy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gt2mufwcvvb.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2hlihgteh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2fxsmskdw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hwurbqiq.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2eqqgpcmh.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2uqqgajak.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gt2bdidqkvo.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxhxqzrs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gt2rrptrehe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2ltdqfldw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2wtvsdwlu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2zovfbfqo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2ostewygl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2rkwkmjzc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gt2husifdzh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2eqqwqdhv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2vjpqtnav.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zhgkkdsh.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gt2kgmpjikf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdtpmwjm.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gt2fqrqsjzl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gt2lwzxmzba.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gt2bwwwprqd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhtyjrih.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fknieuzk.html


<!-- 参考信息 -->