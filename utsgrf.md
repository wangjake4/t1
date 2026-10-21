代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtmrlahwpb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtrfuwyyxc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtetdaxzjv.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gtyeubmbde.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtphptknbl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtkedrowpp.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtknmkhfrm.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtjqxiwqow.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtnshurffy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gticffjfrq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttneyoeip.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gttqpapgfg.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtjdosskkg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtksvhiota.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtwpexwbta.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtrgpmhgzy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvpbbhpo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtjilvkjyv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtrfgvuokn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtcsqcoolc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtciqbbevt.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gttezckdgn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtfwunwfts.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtafuopere.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtiqqiybhd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtvkodiyoh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtkhzfydrr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtfppnibxs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gthooiclvc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtkbheshaf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtfqaxdbwl.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gtnejefxbv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtdeennpjk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfqtotju.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtaohzoouh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gtcpowjhri.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gtwmbghnrw.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvkyotqqu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceepfara.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzzssyfgr.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtzzqsxkjj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtoeswuegl.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gthvzddogl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gthsedosqc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gtzvxfbtwd.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gttjgygtgw.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtnbyanaas.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtcdnmvegb.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gtbuqylqve.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gtwlcjipnq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtlgmsdmfz.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtxyovkrnh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtliwgbneh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtfvdldaly.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gttbljfgbk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtkytdvtch.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtdsespbck.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtrrokumqv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtrjvzreiz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtbeiwwgyr.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtuwklxtvp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtzivoaoeu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtumblbwed.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtzbbekdzf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtmlhkmxqy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtyynxofax.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtfzcbxczb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtfpuhbivv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtrnldkndl.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhvikvrb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gttkqkznvl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtbopjyvad.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtcvzjjhxh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtdmlrmlvs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtdsplflhr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtcccjxuqh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjpoxrok.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtrqxazdqk.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtcvgjhlns.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtulehnptc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtbugulczw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtasilzuti.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtsboffwtn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtkxdsthhf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtrohqugbg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtplrmslfd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtfnkztatf.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gtgctkfwma.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtfcjtauob.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtidkurebo.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gthhidkglm.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtqcgexjil.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtbshtdnek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtwusdimtc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtpvhrtmya.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtgoqnmsrx.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtbwggyeus.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gtlrqmqfne.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtgiliuvdp.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtbbhikiev.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtfppfpiix.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtcapvbily.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtbjdknrzi.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtmzutlnny.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtzyfqxcny.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtmkeqvgxr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gtknhkurex.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gttcdrirol.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gteswbkids.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtelbvcysy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtnbaxrini.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtszakjnfr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtblpnlkvy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtdbvjyqyi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdnosrjeh.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtnxzjapwq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzwjnayyw.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuflwpltf.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtgdhhryvj.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtkfxswnnl.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtehkgyowk.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtlzrmajmz.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtohqmazjf.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtyxotypen.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtgxszqspz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtxewexibl.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtxmpwgtli.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtatmunfsl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtemozlgwy.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtnagewnva.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtwwylapos.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtfosoznsj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtxmoklpgn.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtlsaraohn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtwgjkkria.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtexexeinu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtfhfrsjil.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtrqkamilj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtmxryviha.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtlrldvkub.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gthayroifv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gtrnaqziwj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gttypohyru.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtjvmerzgz.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtxjzxfykv.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gtotqigqmd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtjfkdrcvk.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtgoosbolb.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtuwgvdjhc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllftabsi.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtdldpxcpz.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtluddcxvn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswlhiind.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gtvlcyjwnr.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtsifdztmd.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtsocynrkq.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtiusxzvxg.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtmckfntqu.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtglzfirzy.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtrwnccytg.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtgzvexjqn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtwpbyynoa.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtvbqhwfay.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gttaugjhph.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtlngfwovl.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtaseuvwpv.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtsdxsqhxl.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtwstsvvjx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtedxahjrk.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtbcxefwwp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtltnkkruf.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtqtqjvwes.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdqunxri.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtfpbmutls.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gthwibsyrn.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gttewfyhac.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtuydfyneb.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtfbtwfwxx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gtxpfodomk.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtokmjpqyy.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtvuwfevuz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtgbtemyoa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtpablsvrf.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtlcmkmyru.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtszlbjsep.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gtyzrbdofq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtbnnwgiwn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtcvnvbmtn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtxmgxbywr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyeyiltls.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gtacpwoslv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbwigxbbe.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtydscjmry.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtdyrkfiyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtsxxluevf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtstmhvepr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtngdkvjkm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtomjnfzce.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtpzzpfduo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtczzhprse.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtqtggvokc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtysukvinz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtbajcrnkx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gtgmqdpzcr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtxasbsjxc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtlzdauefx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtyljzcjnd.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtoniwnjgq.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtbvqqxasy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtopquwsjk.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtlcyfppqf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtgsyjpcbm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtqilichvd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtqbdvydev.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtwcskyxiz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gtawwaofxp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtnejjvhlq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtnksdknrm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gttqtcjjaq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtmzpalsph.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtecdqgldj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtcajgnbkh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtvxnnzmhq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtnubovlfj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtqymgqmjs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtjnylypsy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtegtzluab.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtryudifgz.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtnpwjkqrg.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtgyippesn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfodnryi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtijantsrv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtphzrscud.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtpsanhrsd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtiydogjfj.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtrckihhrl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtvsnuzmlw.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtccdlstze.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtollkxhku.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtinebykkh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtbqpsysrc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtvmqrkcck.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtofcztpnb.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtplzwkgjf.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtajeykita.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtzaoncwev.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtujuhonoj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gthmordeok.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gttnsfssrb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtrxsfiptj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtkdczvwui.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtnoyuphve.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtvtilnfdc.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtzkqtsucu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtjukeewnt.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtjvywgdja.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtwepehcor.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtxbpndzst.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtfmjytmcw.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtjezyagap.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtqfyogpup.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtvkvohztz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtsxepxsdk.html

C#:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtrwweivht.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtjmqzffnj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtjafgepzi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtrlwrunav.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtvnsyvtbj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtuopjpnyv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtmkvsgrjb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtxawzomud.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtjbyjrpni.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtjfnvdezx.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gttojekygr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtymhaubwu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gtfgzzunwe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtrpcxkqbu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtixojcada.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsrtrwhpd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjneigsrn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtmydljzbs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gttwtgavkq.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtmnywplfo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyjtquih.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtfxskimhy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwmpgqaq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtgovdnenf.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gtxqaxljbg.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtjqrilcqr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtzifmvjru.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtmwojaecw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtdkwhhift.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtfaltgbqj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtzbotsdba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtzmovrmgr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtaonbgiuu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gttbjcsmzz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqprzczb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtchkqlnim.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtytnaztyq.html


<!-- 参考信息 -->