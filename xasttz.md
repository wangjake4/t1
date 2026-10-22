代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2sdqxzndt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2hzysllpc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2ysofijhe.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gt2nasdwrwv.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2xbnqirbd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gt2cxfqwucw.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2uxktkflq.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2uphbgidl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftceiese.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2jpwahyaf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2hdoxqmwe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2gzrlofve.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2bvqxqrit.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2zinrvazp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gt2gwrojbhn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2spumhhiq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2gnytnwhf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gt2lkhouzkq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2owqexfhe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2hajbyyvf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2jzcpnjpl.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2bpfxmciy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2rcagakqe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gt2ctidoxbt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2taetkdfr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2abjlfagm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2asctkbus.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gt2aoqonztw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gt2oppolewx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdmtblvf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gt2drpiyhzo.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2pggzzzjd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2devyvsyv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2gfusoxqy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2ggcxhbus.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gt2trxiqres.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gt2arnxkdbn.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2dvzedeoz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2thkgyxdp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xkaxtbgb.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gt2jlvanwea.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xeyifdpq.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gt2qysxnayk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gt2qfpsvajx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2ozseldhj.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lelozkwk.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2qezoayii.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2wewqkkpz.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gt2xswbqdht.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gt2ctaornnn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gt2bmdfoasc.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2gwjhfant.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2tldmnbbl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gt2pgahllyd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2eohsmera.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilnxpqka.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2kkegaoej.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2ucntnakf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2tazcsvtl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gt2noypgiza.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2vgkktqtn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gt2irixvybz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2mmmuricn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2fwwrrsvw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2dfpdkkis.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gt2ujznnldk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spsokint.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyvruxes.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2hgbawhex.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gt2ycqiffav.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gt2urlswsga.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2vjiakbeo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2yxkrzndk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2qnxltdoh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2rdevxgde.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gt2ifaifmpv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2qpttdbvc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gt2ngdvzxzm.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2wamsbaxl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gt2gfazvlrh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gt2dbuzvfqd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2rhugheyd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2whiecmto.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gt2lggvlzll.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gt2cpqjoqji.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gt2uerbutww.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2kplddzns.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gt2tbhbwien.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2vjfkvdmj.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gt2juwolgch.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhzorkac.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2usvagdzt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2xqirqzuf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gt2lnzooqpa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwjmlszs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2qwutzpcx.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2ojigxttt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2lftjcuyv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gt2ltxcyooa.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2zdnzhsuw.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2ymcecuin.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gt2ioheqmzy.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2fbsjehun.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2wnmbmgym.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2jvwqoeup.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2mvrvxuej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2dgeivqku.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2vdbctwmr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2sbjnncjc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2kmuwsmzb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gt2pvhgejwh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2mqwlixhl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2wpjglgvx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2ptzbhwyp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ltanpqwk.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkzfhakb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gjnqjcxa.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvekpzhj.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2glycdplo.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qumjleuq.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2lqxddihr.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2apkhcnhb.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2byuizvmu.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2gbhxsxng.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gt2keqxyxaa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2kajcwzhw.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2nloscwpy.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxikzphh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2bztipmma.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2yuswbmqj.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2fhoqueey.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnchojuq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2qwzcxbqb.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gt2xacteioc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2tajamnoc.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gt2cxngrjit.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2etofpkhp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewfkxjxf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcqwpqdv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2fvkrznvm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2lsyccwzq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2nouhvktv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkqvholm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gt2fsbssrwj.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gt2fwfuogyn.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2nforzngf.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wewpaeqx.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2guufdpnn.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clofzceg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gt2qnsbjwqs.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gt2jkxasnzv.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gt2zfpaqwsb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2jjqbumua.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gt2iyxypfgr.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2cmfsverd.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2rnaxwbxw.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2aycrfgay.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2zqzgqlic.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2qhwarmtg.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ewnoetbo.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2avorcwjp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2ifhwzwjw.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gt2xijabwau.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ansjcdbs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gt2xeonsvrj.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2bryklqky.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mltavsyw.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2ifscxfyl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gt2pabecrpx.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gt2yziluchu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2detbwkpj.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2bhawxsyv.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gt2coiryjot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjyhmomu.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgfntfeu.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gt2xwkskbtv.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2wczwhvzp.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gt2fdrdmccn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2djiujpmw.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gt2kejoocqe.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2nbxzyviy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gt2liubperp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgzwcnzd.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2ejojyjhp.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2ifxbhfyr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gt2dimxbbtv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gt2bbtdnxho.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gt2pbhwgvui.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2rcgolbyb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ljffmkfk.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ituospmk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gkdgntld.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlqcoltw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2tuvquftj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kamotngg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2ravqqspd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2pmbsidjf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2fefnsfde.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2dsbqhlwc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gt2pvpqjoqa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2rezwidjj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gt2tllyddtu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sryputqn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gt2hbvbshng.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2vihkxkae.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2nepmgvpz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gt2eetjzfco.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2wfkwezim.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2zqdztulg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gt2hgbzfrxo.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gt2ukvmegqm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2qpdoeysy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2skafvzxi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2fkdjbzos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2ipkarxdu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gt2cdblyivs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2hyrwymbp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2jynmrbak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2iuszqlct.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gt2ugritsgk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2dfaytpgd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zihmqzke.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulqnfwwq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sososwnj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2chvjxhbd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2phezxgne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntbsszwu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2ewmayykg.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cetknyvt.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2uiegcqtu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2qzkxvyxx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2mwryghta.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2ksigxfqo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gt2dkvxawaw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gt2oqnulxfw.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2dzhczjop.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugqyqnii.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2vdryonse.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2nfebuoai.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2deowkcut.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2lpnzyyst.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2jgofxkch.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gt2qfpappbt.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2mmhbwikj.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gt2rqipeluv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2fypqzsez.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gt2jemztytj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gt2mawopvkd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gt2ykkzvgge.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwtkmiiy.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gt2cpwncxrw.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gt2unhkwwwu.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gt2catusgaf.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gt2ybuhglyc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gt2ndycctra.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gt2lbquriwx.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2ytvzlrrg.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gt2tjwjorfr.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2hblxonjn.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2cagqroam.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2vlfqktcz.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2tuwnpcyy.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gt2lmuzskld.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lspvrwvn.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2jkokcjvk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2lqzfsxmk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2qzhnbwgz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2jedvupaq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gt2oomcqcvd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2ohewfxzq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gt2wwpuzquz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2cmiyuohc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2blgovzrj.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gt2ymeypwmt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gt2cgulbpcr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gt2qgcihngx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gt2oombstgh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gt2ouexhlil.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2havvssvc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gt2agdyapny.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmpamzcw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2afgbwlno.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2cedjtibc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gt2nvajczzn.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2puhknkjr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhcbivfj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2wyxtschm.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovltnaok.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2ynjiuvtv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gt2ejlondyb.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2ibxvbjes.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gt2zxqquwbl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2wtojeyyp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gt2eaajrpwl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gt2zmgfojss.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2uyqzdqgg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2mkhwukbx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2kfhdioow.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gt2ddcnzmxt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2teiizmtr.html


<!-- 参考信息 -->