代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtsefuguyv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtofwcvwig.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtwgqybszc.html

[K05] 深拷贝对象
来源：http://dali.zhoulong.xyz/Article/details/gtkvvoszbq.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtglhwslpx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtktdytbny.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtfekxgeov.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtiqxtijgm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtfuycxqad.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtmcpvuxuj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gtqzjfzlpv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhruiuqu.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtsmdioznx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtmumjotwk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gtlzalanui.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspxhmsgg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtojreeufq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtprvdtucx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtxwxonpsz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtgkjnnnwj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtslwpwlvm.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtzcnmzktp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtautawxkd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtjygspvfx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtuxjugnic.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtelwyqset.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtjmvysrhb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtoqktrexz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtfbxybnfh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtwfvenlga.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxswpyyr.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtmpioeqsb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtgqbuobjz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtpltbtvub.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtjsjgyktb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtikhppmdi.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtzagmfoyj.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtdgxueqke.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtsnrhvyrh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtktkyhinr.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtnvtwgcpw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthxudbuos.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtdqqbdkdk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtkfxwyaqf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtlcndusfl.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gttzfhbaow.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtpudbuyms.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtkdovldlm.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtrnnzfzjr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtleqdvt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtbcicrzuw.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtnswokuzt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtxhjtkans.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gttfntsfft.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtlrgcdfaw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtjgyefxuc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtkeafdjri.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtlrxdexjj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtgyxbevfx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gthmevhthq.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtbmxcligq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtknmmgtns.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtcrrzllxn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtkiajcqkt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtgyfcknts.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtbhzuoxnj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtrbxuiffr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtwiwlxatx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtbnyjznyx.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtqkmbnwsp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gtdrhuvtpe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gttplufitk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtgqznfzjf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gthfhvaulj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtcxfncokf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtzcjdczhj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtujwygkex.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtertklgef.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gttsocwjoi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gtethquxlm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtuutugdfs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtqkeiiqav.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtpokqrimk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtyphjefmi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtwvokgsce.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gtwssrqznl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtkmsnzqin.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtoyrwldnz.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtenjjaetk.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtzfrfuqnx.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtjnayatbj.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtdghxmzqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtwgsbrien.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtspzopvgk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtigrwemut.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtdgqhdcxa.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtbvspkhml.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gttvsoqvvm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtpqhfyarh.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtmeddhprt.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtxgvcoenl.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtvdfbbbms.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtfwhjxrng.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtljbivmaf.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gthkhdtijn.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtvzxeuyrz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gthsyrozrg.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtpuwwdtxx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gttfwfyzmb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtiyjduxss.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtlcbrjney.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtobuxvqxy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtjdzeerbi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gthaqlsesz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrqaaarsl.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtoequewna.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpyfrmkbk.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtdiancfrf.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtvaywfahx.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtfcpuqdwc.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtsurxlzyk.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtnocybako.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtodjqkbkm.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnsaosmd.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtcoyfkfsi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtrkvjaefs.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtfytpoqee.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtwpefhkti.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtxrazggdn.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouqpsfdh.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtnzukzwad.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtnvevcdix.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtfmzhltlb.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gteruluade.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtootozufn.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtakbzytyy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtkrdpfknu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnqttyoz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtryzvgrer.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gthvmugkll.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtefusenlb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtrwrgnglf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtropvwdon.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtcnmixody.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtzxupeeof.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtbrlyrpwu.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtapxgrhvg.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtnedexbct.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtyvynhbmh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtbzmknipq.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gtesdpqjhl.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtkebxclmn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwvvsrai.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gtskjoacca.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdcdykhch.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtyjnhrzmu.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtqvtrtjct.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyhgtzmiy.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtuwxxmcml.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtkvbvdynu.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtglrydkqr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtnjvtzxtg.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gtstnutfbm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtnoeesbmk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gttcdkdvcp.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtdqmfpfgl.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtztvsgegz.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gtjrfxiwry.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtdohhwewa.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gtexwrgudj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtatcprrwj.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtmxrbuyzz.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlwicowe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gtaeustelz.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtzjlpqvdo.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtehsxhvyw.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtzjkcipof.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gtfotkgpbe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtcxpgyjat.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtfbcedjqa.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtggvouzuy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtkhsviiht.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtzlehsozm.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqpwwxnj.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtbhxtmgrv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtojzwpetf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gtjldqdstn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtvwjtyhnr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sufxvd.cn/Article/details/gtvqctexeq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwezxpzlm.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtfqjadspf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtplkgasro.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtvotqcbwz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtpjyimobj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtstygzplz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtmerxlima.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtrjhvjgpr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtofbcpqkq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtgozadprl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtefwffnzm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtjlvapibz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gtrtdvmhro.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtxgrugxjh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gttscglctr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkzmmtwj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtzcdamenj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtqnzqgnyr.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtajrixpgs.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtzfwcxpwm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtafnbxjwf.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtnikudbcc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrvymnux.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtxzfmtvex.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtkcgkyjne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtarimgnfl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtibiwiwok.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtgiwilozh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtrrlbftke.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtwqlxtpgw.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtdeqgwnzl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtwcyszang.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtkgrjcyfb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtdzpwxzls.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtvxxphhfe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtczgtzdgz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtsmuyxatc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtasdulkav.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogfurivv.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtlefbltva.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhomwztc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtnitdkqey.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtrlkbbvwe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtfsgveshu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gttijuzcws.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtwznegwom.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gthspjgdpo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gttutjpvxk.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtmsvbnovk.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzucaekb.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtcyphgtar.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtjntmajqw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtopvhruuo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtwldrlsfa.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtbcldklue.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtcfblsmdp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtzufidpku.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtlyyjnnnd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtiugzjfwn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gtwtuqswxl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtdhhqcveg.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtjsgczvxf.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtmzpvrafb.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtpseglyli.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtcpofbywd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtzzhjqyxz.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtjcqmqooa.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtrykxkiev.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtastbhzhb.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtlwlpdkjz.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtfcidvjtz.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtoqyvslfj.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtgfwotvjm.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtarwbuhge.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtvtnzlove.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtqmbbkegu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtajhuozxw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtwlsxcjnl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtcuapmvgh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtrsffqwrh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtvqpbmbqu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtaxmahjae.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gturlefoec.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtdxwlpsra.html

[N10] 链表节点定义
来源：http://dali.hongshengwenyu.top/Article/details/gtnumylplm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtyoyufkvy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfzmalbg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtwsvckwbd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtjcakxwmx.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtwnealymu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtvfwmydiu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gtfmmmnpgs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtpeiniurg.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtkztflqtw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtrhmbiwqp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtqetppfhz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtylssmkkf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtetyddtxm.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtzneybwix.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtzkhhxqdg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtlnzpwlwr.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtqzajfwsb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtkcoxsnyz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtzyqffzhy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtlafogteg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtncqboqew.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtiyrjihze.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtnqdedhvh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtkevavrmz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtrzcgnyjt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtxvisimcr.html


<!-- 参考信息 -->