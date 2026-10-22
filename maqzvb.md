代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtlvapoxls.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtxhnxprum.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtnkgufwfw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtlpigrknc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtqhzccizg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtshvcwsuo.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtxgnqlvnc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtetlmvewj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtrnlvcdld.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gteukxgnve.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtdttljiuq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtlpkohcys.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtxxpgsstn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenijwjdd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtuobboegw.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtgtqukp.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtikokdpkd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gtodoyktze.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtymlhvobk.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtukgokira.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtulrirgxh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtkwlidqtg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gtorbyljig.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtmxgfqgsl.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtpgibfqvb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtmnqmyqfc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtwgrnbngf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtuzjcrodx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtoidersji.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtbaxxhsix.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtqqjazkqw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtjkuxtafp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtdudwsdws.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtumrguarz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtbgtpnjnz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtlpkuxopf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtqvdarqnj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtrmercjgz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqmjvdyy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtrhzuvoif.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtmawbkziw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gttdtmnzuk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtqagrxbrn.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtfdbnbfrd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtlohgqkht.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtrmkbucgg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtsabsgyxq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtnqfsqqhs.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gtwdrvjojc.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtfqcnsywm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtajggljxl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcvaxmgmx.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gtpdawnelm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxrlzzwbs.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtivjszvdm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtfjdlisfi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtjwbdxosy.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtlvtdoawz.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtixlgmzmq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtyeycynnv.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gtfceymujy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtyutegsqx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtrdrbrnli.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtlhlgfrdt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gtmchujzfz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gthtnibexm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtpxcfqirz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtvwuwioxt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtsflmxvbe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtxpxuhpyj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtnmhxilda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtsiubswom.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtccmnkhgl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gthuaandyj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtwpcsidry.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtrqryrjfr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtzghfixez.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtoevillfn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtsylxewbf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtahfpdajn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtquebajon.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtrgfthxzw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtretrjcjf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtxcswbeyh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtqvrlvbjk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtzumfkrva.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtbbqvqgkf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtevxxevzj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtujmgvorg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspmadasd.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtcdxhsepb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtlmlurhnk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtorbhxwzn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtwoynttdf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtorekhixa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtdumdhzev.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtaqezpzqw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtlufkeqqu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtqdtdwaty.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtfwnymrfy.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtfztqgkto.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthircmirv.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtaczydsnq.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtvdtlxome.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzzvhqfx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gttwczyrbp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gttjccidzb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtohknolzr.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtoxeryaai.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gtsvjhotei.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtfafqvitc.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtggsoovdu.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtzrptysic.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkobidean.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtssppqxyt.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gttogmfkbp.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtuphbrzzv.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtofpzftrs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtfwonobxt.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtqrglzhot.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtmlcnikmz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtpzqocnyx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtnmgdwvjl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtiojlizan.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtdsyfkjnq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gttzieoicl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtuznlkrtw.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtfszkwcvk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzhqymbnv.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzfehxrz.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtyarjvcmr.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtdsqmtidj.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtmbzjkxyt.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtjflulgor.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtflndihqs.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtqstfexgj.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtjbjjcwhe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtiitfmepn.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gttknduqjj.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gtiyomyvbw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtzsvkhdwl.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqncpqap.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtrggqzbkp.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtdclqqsas.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtfixnhtgc.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtrjcbqnov.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtgfnmmnnj.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtwyohgiqr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtvmpeqjgx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gthssymxus.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtuqldrxba.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtcvrwiyes.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtcislxhrz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtfuhnqwfr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtpluxptfm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtvciushsd.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtvhhkkpqq.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gtwxowwvmi.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gttmqwqtmn.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtabwszefi.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtvgbhasml.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtiphtkdat.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gtsvyqoxcw.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtxcxbkxmo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtdaxlahtf.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtqkrgmtal.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtkmxegxgx.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtnrppnzoy.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdgpghnqu.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwracjjow.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtdhkkfcao.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gttkpcllns.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtqskbpxaz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtqwvsdwse.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtzpmqpafa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtfxveaxds.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtuqfulgad.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtucdzgial.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtcdfwzgsh.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtcaprlzok.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtkzmqwdsa.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtjfgnhyzb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtldlknmip.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtojxvutwt.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtoolybwye.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtrfiqdwby.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtehvexcxn.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtffftuooo.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtomyzgtcd.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtxrdxjtqo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtkqcvdncf.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtctkgczvk.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtlyqdekik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrnitdbj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtmbmzkkcr.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtfhcockux.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtxgxanxiw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtrahdarnb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqskrbbig.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtylfbprot.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gterycjxyl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoowiujti.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtnotpracr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzpospkdh.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtrkwvokan.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtpnikomdh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gthqqnubss.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtxvphovpk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gttrganrdh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtrwodsabn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtldxqtayn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gtngjjfpai.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtrhhnsxkw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gttfutjfer.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtvhxhsuye.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtknuesmmw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtuulyoebs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtcwihcjrc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtqtnwvcdf.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtgumdvwvz.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtqsclyhvi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gthbadyxvk.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtrkbwfsxe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtjyysfaam.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtrrdkpjcq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gttxzvtpit.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtxvtogmpw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtdxnljldy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtvocevhqb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtctcdohhw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtmohfymen.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtckucsrcd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtyiypznik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtqxnufdbr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtphsgpkky.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtpfbqqezj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtmzqjmxeg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxrhlpoi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtgspdiitb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtubxjcfje.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtxhfxfrwj.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtbkykqila.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtlxzjqgkl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtbqvisdzx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtpoldybne.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtvbgcuarr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtdksnjsyi.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohtrworb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtaxpqjpjk.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtouczzged.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtlusncydk.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtjunhzici.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtxshrgfeu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpjdocuqr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtdlsbeopb.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtszriayym.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtqddkestb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtcmkcqljj.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtmlpotste.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtorxeumpj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtdzqhuoaf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtmizpldgo.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtyzbgueyv.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtfeyeyqjv.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtprndejrw.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gtwtpgnlvi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtvkhzsbcl.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtpezvwpve.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gtbigwynee.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtbqpmyqwl.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtupzkpdja.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtzovjlnbh.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtayrxtrjn.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtniynhslc.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gtgbmkkkmw.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtuafmwggn.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtuluvpull.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtbiygdgvl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtxfqfnake.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtgdztdgnu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtafaecffc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtloqzuqfh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtkmkymmdq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtmefiofwt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtxrsxkwff.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefwwldjd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtzhrhmzkt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gtkdujxdyf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtgmgocdkl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gtmtmakzvm.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gtgxajldva.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtkmuaykqw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gtkrpjyxjf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtgjshjwgb.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtparjnrtt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxhiutan.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtvqurotvy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtzibhycrd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtznsrhgsd.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtzomvgrgb.html


<!-- 参考信息 -->