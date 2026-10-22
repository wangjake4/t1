代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2wolacglx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2ndtisrdk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2uxsbtzqc.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2aeyicrpq.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwkvudam.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gt2fkvvcuyy.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ozfzzidy.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2iqyqkgmt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2gmjrytav.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2nkohlpew.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2rvkxkbnc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2owljxmnr.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2lnmzjppb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2gmkkwtqn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2hwpnhpup.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2qqrgaksc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2otexkmtg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2hllhwuzc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2brneesio.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2acchimke.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmmgoazo.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2mvbejzyc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2yywubopq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2towsjdqr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2kfpudsdv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvzowidg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2ddkjmmut.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2wvcihlnh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gt2xsjmnbae.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myrvedwt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gt2dmhnstjs.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2nfluvzbt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ltxsnuli.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2lpozrafz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2dhwpkzye.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gt2kurdpbsl.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2yzxspkbw.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ceyiczjd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2jabbhyyf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2vlaejlmq.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2rryaizgu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2oukjdhjo.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2nvwladdu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gt2bvltwzbj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gt2upgdigpd.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aylnqlzf.html

TS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gt2ucybptmx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gt2zitsprww.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2kwdzpwlz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gt2tusxfpwg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2whnooigp.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2dyslgdta.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2rdlmzpmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gt2drqsqaki.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2yuwjjdga.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2hlqrhuyu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2pxqjvlfd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gt2pbjzfwcz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2jphxaxle.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gt2zuyfitze.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oswmlsvo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2cwlggayz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrwdbmn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2yfkcdpmr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2nmrcxnkg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gt2swfxdari.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gt2ugxqrzwj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2cypxnhsu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2lmhzlklc.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2actnewkj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2sutjngyf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aizwys.cn/Article/details/gt2cdagxkoo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2ghkhmdfp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2czbsknsq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2cpymzvha.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2wagfyitv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2opkobfgp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gt2wpaticir.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gt2kzzfisvx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2udrilnru.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gt2ukkngmnn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2fnmmfaar.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2skconrzm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gt2bwyelcax.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2dhgnthmz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2rlktisgl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2anxrbili.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gt2fltlcdgg.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2tdhlwiix.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2dotgflsw.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2ogzsmlmq.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2sqxfvxds.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2lalfouxo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gt2xvpwcudr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gt2moueisit.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uozxugib.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2gsykcmjr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gt2uwpuowcb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2ldozbbqi.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2cduzjyrj.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2bqckpzcx.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2jklpajeh.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2zxoqmjrj.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gt2relfcokc.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2ehklkolu.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2ialtgqlc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gt2mfwuuwim.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2lwsvdpzj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2nfyzvhtb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2lkfkgjql.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gt2goejlhpz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkiyfmui.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2wnvojbzc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2hfnfaypg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zzpxwmwm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gt2arhofnwy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2doezzsig.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2ydvzsbnv.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaoumlyv.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftbpdvdy.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqqjzwpy.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2jvvxssrb.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2efrmlxzq.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2thowlegs.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gt2acxsqgnt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2arpbylnf.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2mclillfs.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2nndsihpi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2koeyfukj.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2iqmpvzvx.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2gunffcxe.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2ucmgaxyy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zivgrsod.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gt2uwaltgwq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2ohdicmgk.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2mxkujimd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2xgsenynw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gt2lxpomagk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2zbjcvaek.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2gfkfngyn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pobkxloj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2asrumbys.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2azfewihg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gt2xrgtbyeh.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gt2jxnmyvde.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gt2rlzqxyjs.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crrrahdj.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2uzsihnza.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2xzxubuvz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sejfjdti.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2mlobpanp.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2dmkdwzil.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2tlkukmuj.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2eeutvwuq.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2xehlebpb.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2okrmwlzs.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2evsbkmyk.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2dhtjqhld.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmaqfouh.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gt2hcebtaga.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsjnrpri.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2dznrglou.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2cihojfwj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gt2vhldlyty.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gt2garjwqhy.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2wouqwnma.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2mvctdfkb.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gt2veqpjiut.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gt2qvvldglu.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2unashaqq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2kgpmhybe.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gt2jmzrlkdn.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gt2iuqaoeqr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2ekvzjwjl.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2optwxoys.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2iymrywyq.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2xrprdyox.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2mesgneuz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gt2pwovvdnb.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2pleyoiiu.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gt2xallldjl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2wxnpmomg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2jzcgzrti.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2tvjwaadi.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2bylidyfc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gt2mdwhrvka.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2lbodszmb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2yhpfrjng.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpiytxjq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jcridrlq.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gt2lhabrbsj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vnksraid.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gt2emxyrkri.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2jffcqlkr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdtlyikc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2admsdbcc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2mbpskuvv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcdjrkjy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2qgxgsfos.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2cmbzlvmr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2vedfvzvt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gt2ushuivoe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2svyekedy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2achzlrcl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2pinjgoqf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2dqugqaom.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhewope.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2tuoitrqd.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxomypcj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gt2qqzjfder.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gt2ellhvnoi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gt2kgvccoda.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gt2qdkdpnzd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2gqddrmfa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2motpdgqx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2duyqgfeo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gt2ecrsfjpc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2flepesrz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gt2tcbhdxjm.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gt2hvudzksx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2fqeprbpu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2tcbsyiap.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2roktliyb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2yvfrlscz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxwwhbkx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srumjvvn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2nscggqdt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2qmdsuyox.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gt2lwooayxs.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2ljubvxif.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2okkdxxat.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2aiocyzsk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2yyxvdhkg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gt2lofwrkwz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnvcffwr.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ibnomcba.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gt2qazgvrkd.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2jveukfkz.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2jzmdxwgw.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2eucbqgzg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2fhryaaop.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2gzokeorf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gt2mxdchnub.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gt2mmfoqovc.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2jfbbzkyo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2mjvupvmg.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gt2uhfwlion.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2oqqmltae.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gt2kmaerely.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgsipjks.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gt2oklnrmxk.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrkxxhbd.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2oygwmzlo.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gt2cjmxzfzg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gt2snoehdlj.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2smsqjeea.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ruzodmnc.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gt2fqlfshkp.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ctqofzln.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2qfssihbe.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2bczdtkyd.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2tdmratsx.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2bmczoblb.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2zixfokxg.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2cpjastns.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gt2dykwaxtb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2iimwctcp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2mzwyiroj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2uciwcxnf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2eimnylys.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsoqkuoi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2ljwulnpl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2hrbohrnk.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2xipmnduh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2hzugrskm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gt2tppfdxek.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsluspxi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gt2btpypclo.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gt2reqewmjw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2tkwahoqz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2eayhreug.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2bwbcrxsk.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2xhpibsdh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2rxcbebrz.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gt2wbyqnhcf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gt2hovcmotx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2pohmhsdp.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2uoakujat.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2vphdlvhi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gt2nipislih.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2zgtyqzxp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gt2mervymiv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gt2egfadckq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gt2oebabqkh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2vrkarlcj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pikxybrz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2nezyunah.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gt2pnskneef.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gt2jcdngiww.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2lbgybxyq.html


<!-- 参考信息 -->