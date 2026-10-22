代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2vecinhwb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2zvospgpj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2rpvsswmr.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gt2albkeows.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2hssuyyzc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brytngpn.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ztkkfbaw.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2njmipwjw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2fgudregt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2nvqochzn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2dbsknmwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gt2xfrkemmo.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gt2bfhfxbal.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2emwpyykj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2tkizeahs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2rzaozuce.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2xdamufvp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gt2racdtkap.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhanzjrd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbkxmlpe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxewajdz.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gt2ycrcgtaj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2dsslexcw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gt2nnhramht.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2zkolkejl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2tqkhivgb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2kaxmfrjl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crzvmcje.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gt2pgwgkazw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2ujxmnard.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gt2efgpjzcj.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gt2fkuchcyo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gt2ribecdom.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2gksxemho.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2oiuulbab.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gt2uhmmwvtm.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2wkyfakzf.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2zkpgcgua.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcbyifxg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jrehepie.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2teorkxmm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tqlrvyyl.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gt2xhwqikpm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gt2nlqwhptc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2zzubynrb.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2rkzusmnf.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2epprdgij.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2kuvzhooe.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gt2virkdbzz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gt2leprqrgu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2mjeomxui.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gijslrcr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulldmktu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gt2ujwpvtqr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2tqgnfohm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2khyyapdm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2wdjcsgrq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gt2kzkgveay.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2zcfjqlun.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmwudtpt.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euedwxck.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yeyftcnp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gt2vnkloqxd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nudmbxye.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2icuxvqdv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ietczglx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2fszovevx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyssryav.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2ndqnjeoq.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gt2hsrhbzwl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2ssiukzus.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymdpxvaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2ioxhieik.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2uzcpawvx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2uzkipqdy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gt2nnqoshly.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gt2gnnfyzbw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2gazidijb.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2byaonpdh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2vjvfintk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gt2xgwksgkj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2rgkobhem.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2gfxipbpj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gt2nraaslze.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2dgnsrplm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jutcrukq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2cnpkoljs.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsabedtd.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbgtvvbv.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gt2dqyfppuy.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2dosaiebi.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2syigcezw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2yadebdcl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2pxrqxruy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gt2gbtuvosm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2qzxqgtar.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2ufzoazeg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gt2xzhqjlyi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gt2fdvzhupq.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2ttnvsmtd.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2tfctkqxf.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gt2dvqjioln.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2sdrairsb.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2ysfxlpko.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2hnizybsl.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gt2ntoxzozk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gt2ufaliple.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyrjdliy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ceqsuthv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2gjfdnntn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2uhpcvitc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gt2xdmgvbdt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpmchxwy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2hyansdkk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rtusqiji.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2fnvnxeqi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjrnojzn.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2qsntbhdm.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcvxwnmb.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2itlmfiks.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2ugjshofr.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2syqrplyw.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2bayqqjeu.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2lumsayqz.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gt2qiefmwwj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2yzfkkgyd.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2rjkygehj.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2hazadkyb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2rtaizrgx.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2rajbbevn.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2pnhsxwga.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2ozvpbqcc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2edcskkoo.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gt2jsiheili.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlkfxecp.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2ltxoadoa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gt2plvgmbyx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2pvzaigqh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2nptojsba.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2ciliscyc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2fhisvhis.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gt2juulaqtk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irlgnsdq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2hwbsppcu.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gt2ybukgyep.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gt2ovjeeczs.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2dyircjjk.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2xuaszgcb.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gt2pekstdpa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gt2dnvlqcrs.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2makmiwym.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gt2fqxtcliz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2nzclfyhi.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2mkywiuix.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2xbmqcjdy.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gt2uxtgkwik.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2ntqodfuz.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2kcypqegj.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2dpgikwjb.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lksodkxu.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gt2udbmfjlv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gt2okgchojw.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2sfixccps.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqdwqnma.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2zpywfaby.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2kezorhne.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgalncic.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2xwjireeh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gt2lsjjpqms.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jphfsplx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhcxahmr.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gt2psjhkqmv.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2iwudytaz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2xdgbvfht.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2scwxmjoq.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2pirhlcfw.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2rgpglsqc.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhmqncle.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gt2cvfzwfgn.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2huptfbli.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2twvlgcya.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gt2bsljliau.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2lihaixmy.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2kfirdbwt.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2bdcinkvx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gt2gscbonya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2xmrmlnfn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2erghojma.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpimlfgi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ybakzcgl.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gt2wvwxmloa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2glwwqpcl.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2dcvrejbv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2fzjbutyq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2kvgzmrtz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2vqkywwnv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2ezwnnyvd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2exzzqbfc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2vupqnrtq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gt2xkdzspbn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2jqkughqq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gt2znpzfofs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gt2fpblferk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gt2wzfpjxpr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2bzdkxgpt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2ruointbk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtxuiets.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2sqbslfij.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2fekgryuh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gt2dpvrxeha.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdwruhom.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gt2znbqdvxw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2kcoerawy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2dnvehmec.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2tumblkkj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2ctexdxbb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gt2xsellbaa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gt2ddsltdoe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gt2uanbrjkg.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gt2bvnrkorh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2bxhtnmqs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2ezrdeqaw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2grfdhujd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2iuchyytt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2qoohpopw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2mfsoniro.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2sagvhjsq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2nkjlfzkf.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gt2ariltiah.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2eyjgdkah.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2enzzcxks.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2xutwljxb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnzfpdgn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gt2llsurqsk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gt2raaxssli.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2xjhmdqft.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gt2mmxweptx.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gt2cfagoeko.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gt2gphgjhkw.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koixlnen.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2zuvnysvs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2ymaglkra.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2ckpgujqb.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jngzfiib.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2saxlgsez.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2yzifdylg.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gt2flhloeku.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gt2wvipceio.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gt2jsutqoax.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gt2hwyrtgft.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gt2nydeiioj.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2rchoblul.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gt2labpyvwu.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gt2jsbhmbay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gt2vevzjqax.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gt2qqcbdeac.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gt2vjtrlwox.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gt2ylztsjme.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2hxfakply.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2mucmggus.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuyyrwys.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2voaulypf.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gt2pzyajakq.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2dyoatpmy.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2skoarprd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2yhsqkpiy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2egkaacdp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2joxkhnxe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2dewtrsco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnotugkr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2sekeewkd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2ozgzzagu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2yaprffeu.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gt2qdzxnxoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gt2pztedtwd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gt2ijrqrydz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2vyjqneof.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aninwwmh.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gt2snuwjylf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gt2eodkfjnf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iowxnfml.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gt2ctnuovld.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gt2iokyhwhl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gt2jusxkrcu.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2nflfqpyx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeyihxwt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufncbinv.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2ydiieibr.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2usgxqjgm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gt2dzxvieaq.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2tyncddjs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unvbzzue.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2ryyzlzcb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gt2joiweptn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2uclocfqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pehiahkb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2hbehppar.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfreltvd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gt2bvhiexqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2xhcmjmxt.html


<!-- 参考信息 -->