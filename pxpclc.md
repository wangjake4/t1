代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2niudlkhe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2hhlcqybu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gt2evktnrod.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2qxyguekh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2uavzthwh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2wvmpguwi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2mlhvbkbi.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2uuuehxcz.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gt2claukqde.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2apiejxnr.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilbokcgz.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2gpbsdwfo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2udhbtfpo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2norvrwpb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2dacwfsfv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gt2urrwkvlk.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2ttnflhlq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2lknoahoq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2rcrltjbd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2ebzzlzzr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2jilhlkeb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2nldbqdsn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2yxqwzsfh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2latcyfib.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2uzrnzasr.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gt2jzjnmful.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2riijunmi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gt2odgjnhrd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2otetawlt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2rbshsklx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfowwydt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2xpchjjfr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xamgyeir.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2qzllecgg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlgjxyae.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2fuvbjvxr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2mfdqvvqt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2yynsnuzx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2dhogyxgx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gt2trpsldqd.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2jbivarbk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gt2zoeevelr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2vfmctsqd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gxlexokx.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gt2qqszouzp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2awvmzilt.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gt2zrtukjyv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2fhhkvucj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gt2zcmtzhzk.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2atwsesit.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2rgoaclhv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gt2xeretkeb.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxvjizfg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gt2eivpuqtn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2hbkxmlni.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2rclyvpez.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2ktedjzoh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gt2ysldsjcj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2zwzybfhr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2lrjzneri.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gt2ikfvscqf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2chgyqtzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twbrrbnb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2fggthbdz.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gt2gjkdtczr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gt2biepvikc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gt2slkycmwc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2wllqfobi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2bsaglsiq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2tfkglbiu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2nyrhsvwz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2hoziojol.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2efrddrcb.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gt2rvjhmzev.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gt2zbrfsdby.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2nyadzmko.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2gyzbyaxj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2ikzwxols.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2zaxcmoct.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gt2iyqgkfpp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2tcvnsakb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2psukohkk.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2yqoymgrk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gt2ggtacnya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2orvmwpaw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2wjekhdee.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2icvchcak.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gt2pznwkmnj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2sxtwivpu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2rqdctysp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2chxuisdh.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gt2tyghxmqt.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2ckgcihbg.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2psizfjnt.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2olmqlkdz.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2mkflwcit.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2orunqhnk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2prazvmid.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2zhamujeq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2pxofivbr.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2jkzwgnkd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rukfcrpn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gt2yjmdwqfu.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2hkvfpbai.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2jjwvjqlb.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gt2cajxozzj.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2bdrsyjuf.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gt2syjyyqam.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2attjblbn.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2zqwendhk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2nwvszfei.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2itrinkie.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2tjvrdvvx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezrvbdaw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gt2fvwwjvtv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gt2bsjkvmjt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2vtkeejfs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2nijmikzy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2yfsxhnjj.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pncmwgis.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2tbtrujda.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2fwfnubns.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2kmzsmmge.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gt2qyvgadrs.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gt2ojvifbzy.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vecxsamw.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2kbtumouv.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2vcecxeti.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2llktnlgb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2dumtgaof.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2ycqzzgyj.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2irzyhvqc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2yuporkdf.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2crejkzgj.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2cdcxfvqk.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2bnofvzjg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2euxlwydp.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gt2oahrkmum.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2hwwzicar.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gt2pvbkbjur.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gt2hqjcxdkn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gt2ixvxfoxe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2vjqlizbv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2snuoajzz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2wfgzuyzm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2fwqwnflo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2mjlhtbxc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2vjpcimtm.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2sojbqkly.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2akzmhmrr.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gt2bnrmxlet.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2xegcrypp.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2iccgqukh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2wxjfttwj.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gt2pygeyjhv.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2vdkkaizy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2gkiiohdm.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2beiywcip.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2htftsrmw.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2lsqxlnod.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2lxzoapub.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ynnpxiqb.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2rjnjboug.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2lxbuiaop.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2vbygcjtp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2wzhatucs.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gt2axlotqif.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gt2znzltymt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2kcrfzqzw.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2kpfsweyr.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2zcxeagrj.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2qhojgxik.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gt2rfnwfknn.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gt2akehnkuj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2vnabuezh.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gt2msocohoa.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smkhwcjb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gt2jfebhbih.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wunhnosx.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2ytuopfcq.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gt2wwgidvaw.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2gowcuqqo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gt2zrwgcnnd.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gt2hoegwfgk.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2rombjkcm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2extxislc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2gfumjflv.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2swarrjir.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2epcilqns.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2gbifxxaw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkdmdtyx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gt2aentfalt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2ribbbgir.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2hdarotce.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvvznvoe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2airupqhh.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2pyarmwlm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lesjbuwb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2glauqyrb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2bhxgasjw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gznfmzcl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2mhpdbfvq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2rnlquwpf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gt2lzvofrgt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2cvljncwa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gt2ronjvhow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2tbtpqrjg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2yxwjxyts.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2bhuafsbh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2vkocymqe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gt2evcvyidw.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2iuaixmye.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2dwdmbmpn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvafduis.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gt2fegciysh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2lxibxisr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gt2bnuncwkk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsmwgocy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2qahfowrj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2uwodrgku.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2clrrxkfl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gt2gzkmoadm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2jtvniera.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gt2ojvmcrmj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2ecvtamhc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2ffxxpidz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2kwwmvnzq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2qivwbqui.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gt2jrkpqmvm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gt2pqdlhtjr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfwwrjwf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2tdiiecae.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gt2fnxdgjhx.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2hqpqcnsp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gt2cgsusagf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2zyyrcdtk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gt2zmrcipok.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqwsjlgg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2wlwqnsuo.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gt2sulfqsct.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gt2dsjaobtp.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gt2gteeagng.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2hwwlhltt.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2ghxxkvxg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2pgmqvykj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2kcbvcywq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikbthfhv.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gt2tsyclths.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2ofidvfpw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2oddilxrb.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gt2bwwdpyqh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gt2wefvdika.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gt2egfoaddp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2pagighgr.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2yaivpqrs.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gt2nnnedijz.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gt2gvypmpds.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvxngksz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gt2lempuhzg.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gt2dpqivzfz.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gt2taltkbic.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nehfyiqc.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2yhzneanz.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2isxfwadk.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2adodhpyx.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2omwcuaxd.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gt2dcdzybww.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxywquwt.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2jjeduzon.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2reivzhab.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2bivgahbn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2kmxgyvgk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gt2jhziproy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2bhxkiekd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2ovdjqkzl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2cecctxmf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2caeygfik.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gt2pczzgpmz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbxvxqfs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2nobbdqgy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gt2sbusdldc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddkwamgh.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gt2wyqltecg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2sacplxql.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gt2uckqpgfs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2yscfreaf.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2jshexhrs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gt2ziltdfzb.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gt2lhbjokiu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gt2ztytdqlr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2qwoamvpr.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2yhmogfkl.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2tccftpyt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2kztyuagq.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2qxrldims.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihpxbdei.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2djhwosel.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2nilwenvr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2pbutwckm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2dlqrumah.html


<!-- 参考信息 -->