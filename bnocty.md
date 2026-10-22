代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2yoxdvved.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gt2xnyrowhg.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2lyepietk.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2wyefvnms.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2ccfluyqk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gt2bhpihlxm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gt2gxcsipow.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gt2lfofotnw.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gt2epleggug.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihwevkqs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gt2rlgmxedb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2ubmfkhxt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2scdcrzhn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2shvceaui.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixotvjae.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2arzfgkog.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2ppoqgbfb.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2faiezrky.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2bbezfhmi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gt2eegvmxfn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2ftrsmunv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2wuipokuo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2rufjairs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2chbpelic.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2fhgkrnvf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhjqvhrt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gt2rxxkfqjp.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcdmbxqz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gt2jhaayaal.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2xpfkqeir.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2cmktcgvr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gt2dxcyajhq.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2aewhmega.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2fyuvhmnm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nijshrvf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xnygrbqu.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gt2lhslprmr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlcuwqlo.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2uirvcuun.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gt2eihxautt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gt2ozqbiyag.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2rofcovge.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2popumpdi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gt2ieovhcyu.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gt2owbvhoto.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gt2wgtrvklg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gt2xadnbpam.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rarzpjmo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2rvkwoixc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2vmmfnlia.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2yuatjoqg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2xiuonmdq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gt2srwhkiwj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gt2izkefdem.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqsxiozm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gt2jcfvciur.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gt2eggcwlpc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gt2qkktdfth.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gt2kamvcxni.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2bzlhhdpd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2hynyrunf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gt2ucgtdmkz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2bmufzaxq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2ywcmaouq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2ceauoaef.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2dcodylqq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2viwfbwtb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2zxuftogm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2wlepakub.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2qeurudop.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2nootnokc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jknzrynt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2fbnukzhg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvrjjaik.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2yubwdojr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2rnbpgzga.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gt2exyrewmv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2ppettcoi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2emmyuhyx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2yuhnyftf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfrrhakq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gt2miaxayyk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2uuvmawcp.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2ubeorlcm.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2vfekrohd.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2hyqgugmw.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2malhliey.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2kegxpnhi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2lxtakxyq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2ubemujhh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gt2kyptqgyq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekgoykuz.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2jtsczgub.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gt2ekjrffus.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2ehimxlxx.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2joksmabc.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2vimntlli.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gt2vrlmwxou.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sczbyuta.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2xrkpmgiv.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2imktvfoa.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gt2excafwgx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2xxwlfhyy.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gt2afsqnlrd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2dkcyuwip.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2nxzblkeg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2wwimayth.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gt2qmdyjkzm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2ovfdrdcy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2gclbpomp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zsygnxhm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2zsbtcdpe.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ecwfndxj.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gt2gpnorook.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2yfgszxcv.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2zwcjbeny.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2uwdymnzs.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2uzvhgfik.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2lyxspdzs.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2pjmulmwu.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2cahbxbfx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2hmuiuvnz.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2lneenfuk.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2diayyvdh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2ylmsekow.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2gixpvfix.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2qxiktxjl.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2xpxgrxqn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2xysmsqwk.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gt2otwkegzp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2ttuowdri.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2alxcubiu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gt2qstcxbzm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abrhrsji.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2oivcvyjy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2lnnlwjpm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gt2ybpufyvq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gt2izptndgt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gt2xsumiqsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2gsfrqbuh.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gt2fnolmptd.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2armecios.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gt2eykegpeh.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2ukxhtxkr.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2owyebsbu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2ovtbqbic.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2zxqzpahw.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2kcynybqq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gt2bqxtcvep.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gt2oympfzef.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ogakskdj.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gt2eznqbiqu.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2oszargmu.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2kmjjquhk.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2gzvlivxu.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fekccnbt.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2klxxoqju.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gt2bvomcixq.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2jzambjnc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2zesrxkbp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2wxfrtmqp.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2pdifmukt.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2akxccywk.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gt2ikktbtlm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gt2hoclohhw.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gt2zmxdeeyt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2mmmdxysi.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gt2ygqkmljy.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gt2igcrvndg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gt2cbsowwgm.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2xxivzakb.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2sgmaqsuq.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gt2amqwvfak.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gt2yqbozqme.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2pjcadnbx.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2afafjuvi.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gt2swvtgzvy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2vfgcmbbk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgkqnfbz.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2iyolbigy.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2okqgdzyk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2ilspsjgv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gt2navamyhe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gt2keovohtt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gt2caiiuybn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2uobclzuw.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gt2zbbvohze.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wczvecrd.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gt2irehmiyq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utnhhxhh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gt2pwjxlssx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzyqsqqf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2tejgwqds.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2dvzbgyez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2gasffuqd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jojhdpxe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2qszufjut.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gt2ybgbwybc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2rkzoquui.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgbtasty.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2sabkgecq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2kyhmlgyr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gt2pnywythn.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2taswgidc.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gt2nfshngye.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2wvidmfrn.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gt2tdgxzgah.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gt2utqalxbr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gt2samneqjj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2whzxyeup.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2exdcwfex.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvxzkwwm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmkdfgvz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gt2oarndmol.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gt2oggrouhz.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gt2upeglswp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndxhrtcw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2xakatmcr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2cmidoxbz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2sawazvul.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2enmopypb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gt2mxitzzbg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2hnynexjn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2cvoivugv.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gt2rxiwaefn.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2assyxdre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gt2dqzvlbnr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2llhdcvtv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2ghxbbved.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gt2mrwxuzcj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gt2obnbmynk.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gt2odqebtou.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gt2gguvedqi.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gt2giicejyd.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2mtoqrzrb.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2ttkgkucv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2zkhnsnzo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2janotlqz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2qevvpvqc.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gt2dpslldfi.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2qpsyfagm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2wblsowbk.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gt2mfqpjmwv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gt2qqbteghv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gt2wnoybvlo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gt2juqncwtt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gt2xseviglh.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gt2btbkwlfq.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gt2gzbgtjcu.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gt2ienyfahn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gt2mobwvuni.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gt2yylsgdwe.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2qutijqgn.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gt2otnlybac.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2xusthxvx.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2dssqywjh.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2zmeflqdk.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2gkuxwcvy.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gt2ryaoiwkv.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2wneoxghz.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2jcziygdg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2jxokxqqi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2nvvzchxm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2gopukrdc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gt2dyjemxpl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ioovrnzi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2antjcayn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2hansdddg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gt2zdqwrruo.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2wsgnbugv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gt2qvfbxzax.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iikkursj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdzkoxnk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gt2rjoijflx.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gt2pegrrkfy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gt2vffdiaxc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2jakvuxhc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rbvoxhwk.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2fnjiejqu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2sydjbkuf.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2bjnlohqw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2bozqjcwi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2svvbrklc.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2clozijod.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2jobppmuc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2eouptmbn.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2vhynvblk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gt2rbxporxv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2efhcviyj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gt2chjihfjd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2enohecfr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2bxdpkcmg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2fshgawkt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gt2steleeoo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhzpuguo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2jrwdimvd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lszxeqbg.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gt2hcsyslqc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2zerlbqjh.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2ivgxkcow.html


<!-- 参考信息 -->