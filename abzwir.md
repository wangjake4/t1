代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtshrpynuq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfxymnjd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtzhvnslue.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtxqxwaeuq.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gttbabnfnf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtvtbkumfg.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlhguttlf.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtjagiygeo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtsaezsxxv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtkgsroedc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gthxujelcg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtkcgguhcg.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtyglrxyvw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gttjtvbmsm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gtrkiqsodz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gthvubgrdh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtyiegtyfz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtzpxadzgk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtauafjtvw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtlooufynu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtvpqscbif.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtoyfapuop.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtibynypmh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtkikgvjsp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtyinvvzvz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtcycwtdub.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtsxxggous.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtikxbjudj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtriyzqzvx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtmdklosvu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtuzpxayvv.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtzyfnhwwe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtwmimvegg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtjapnhmfp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtkcunnwts.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtlbiiefbd.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtgkfpwcrv.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gtjrfnxqev.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtqejsrobt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtklyjhypb.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtlvhduaep.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzairiomq.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtsgalfxtb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtjnvehmkr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtdihkqjdx.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gteikoalma.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtrqdcdebj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtwhrtbqdg.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtvbwjevuc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtrcpkreog.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gtmvtnatvw.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtusezcrbq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtwiaelcuu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gtxqzzhgfi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtumgazidi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtglvnlovp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtvoxajrku.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtutsmpnxk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtscgjzktn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtbzwszsbe.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtraxdorlo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtjbjdshws.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtmkrolhio.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gthwypoqnf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtnksfnati.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcxzmrty.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtjycxzmos.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtbwcdjbxc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtkrxplstq.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtdxbxqlcm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtamfmddbw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtgutxkmrf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtdhqxqaqc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtgggqnzoz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmszdrzxi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtzploidzk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gtokunhmag.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gthtpnogds.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtluerutwf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gtpmderktm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gthdfgqeec.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtvpkhiegh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtupxhdqzr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjglsanzr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtwjhczncq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gtaozaqkiv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtiwgkuxwe.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtmfawiyjd.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtsfdwlfgm.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtftqqyjzt.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gthvzkhfxh.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtzhdemckf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtvfxgclrs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtigviiikr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqvkvcdh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtdhskttmr.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtppiixfob.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtgvqyzobm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtquzryyek.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtldicereb.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtmsyppgfw.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtzulrxmwp.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtvxbijiqc.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gtlgybbwsn.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtczmcnein.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtvudympak.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtqbadhipz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtvimfiekf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gteibiwxyn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtxiwwnpvo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtdkivbjmf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtcmarbhls.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtqmxkmbgg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtfgzudjbl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyqerxerf.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtshlqkwxf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbafebjqr.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtvxgvtlog.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtrdzbpywd.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtildvpcwm.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gttucbjobx.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtwvhggvej.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtburijzja.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtisdaqsuy.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtxkhdveqh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gttipbhdxx.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gthdtpvgud.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtwcakurmh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtajycytdl.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtovnzbxpl.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhappuav.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtjnoelaxl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjleaiwmt.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtumjmslxz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtnwivqjqg.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtiyfflpol.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtpqkfhheu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtysnyrcbu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtidyjvbxu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtxtgbbjwq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznuvdslv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gtigtqfhcg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gtbvzheode.html

C#:   Process.Start("ls", "-l");
来源：http://dali.mhx1999.top/Article/details/gtsbndairg.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtuplazxbn.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtxolfsezb.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtcjqjvncq.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtoetanrpw.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtbuqvhsgn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtveboznhc.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtyxaelgej.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtmfingrnn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtirhmoiny.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gtabpnwiuh.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmehcplu.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyjjqpep.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtauifntpk.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtrphdwbdt.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtcwrudsej.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmadwiffd.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtgksbqyee.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtanpdqrhd.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtfdkqtjmy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtiiepbzti.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtjxvgeeiu.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtobnniwzn.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtbmdrrqmp.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtnaoebdeo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtcmimtonn.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtlpraatxn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtjqtoimev.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtusfmihgs.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gtvvqscbvb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gtrenhdpyh.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtrgosgeia.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtgvusipmg.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtcsywavdg.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gteddwrqkm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtwjhcdaqm.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtnlttgmkh.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtxwhjgyfu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gthpwpncbq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtjbbcsbqa.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtsmwqvwxa.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtqqbvlpuj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtbsbtvvml.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gtkbayywlu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtlpfhasbx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtrbnjgham.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemzcgaox.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtjxcgsxuq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteoyqidqs.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtgjirzdcb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtupdaqgxv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtepfqtosj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtdpggtqbs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtxelxmaaa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtygfgeabu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtldpfbkov.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtrcjzpohu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtaqljxokp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gtjfsepxrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtjlufkaxa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtedgxhzsc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtsrhdutjk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gthpbxmmdc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gthqormugq.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtrvfwrqzz.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtedhlrdln.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gthsftflcv.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtuyraqewq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gtkywqisxt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtoerscdbo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gttzcmoyyy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtzcpuqeyb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtbeqhoezn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtdqrtelof.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtlrptocfz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtdjljyuil.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtnhbxeqgu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtqabcgkuw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtukmvwwnu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtwmlzcdyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gthyvkyxpz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtxjdprtfg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtkenyjsmx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtwkthqmmk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtxjdvuljt.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gttoaoreak.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gtyhrmxodr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtygcsjvvv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gttwsxekmw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxvrbtkdz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gtvrpuajnr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gthemoddhw.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtvvzvljik.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlvsqyli.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gtyoeyxehf.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtfujmsfws.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gttfgtotmd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gttcvjnczf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtsxgbbuvf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtrwutoqvs.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtjzyxyvtl.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gteubvvmuj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtylpobbxe.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtstqudclm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtxwfteims.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gtrpvkssrn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtscabgvon.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtijfhvsim.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtceglxmzh.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtpyjiefbd.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtjfcavaep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtgwultdbk.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdddcazs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtptmcpbci.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtcmckhrms.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtjndkmzad.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtdipxlriz.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsgzattg.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtpyjqtmwf.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtjjbzwnyu.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtppojhrmf.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtijfbtuha.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtqdabwthk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtdtwvtooo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtqtrgerkd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtwcrvkklg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtgwcsirdk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtzbwpihco.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtzwzlxhto.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gtovpyeyqo.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtnzewoiok.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gtzprhmima.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtsxziolwq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtcaudhoxd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtduujdlvu.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtsupkhnaj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtpktjfqcw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtcmbhngky.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtvvhxvlxj.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtqfxidipv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtmwnxzzkd.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gteejyuyre.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtltlpgzdj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtnfipcqve.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobxnivso.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtefixxkwb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtlxgkyegl.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtbpuddamz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gteoycwbyt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtcrbggzdt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtvlilyitc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gthaqfnsor.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtmyotytnc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtycfyhnna.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gthrlmddec.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtxzjwrlhe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtjxqcicpa.html


<!-- 参考信息 -->