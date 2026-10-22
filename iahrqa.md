代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddkerupy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtmyfbbrmj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtlaartdgj.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtqresfbwi.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtscsctijp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtyemrytan.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtyignxjdm.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtcfcklodv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtpcntdyad.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtdveoajwp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtebvdfzxa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gtxglpxeyr.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gtiyxkqrtx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtewcbqszp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gtqgscczie.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtgxxcbgbo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gttizjzqwv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtejfytosj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtjeefcnce.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtbcxtykkd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasrkyyue.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gtsdptxkgb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtnmbvthet.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtvqqmzdbg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqciqxigw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtadtklpwp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaruldhk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtvlyvouix.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtnfzkqiww.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtazbpqisy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtnmsjgbry.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtlfgjshbb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtsyoslcva.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtdfggmwmu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtulzseaph.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtvsxmypsr.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gtgccswdrl.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtaavlpuqy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtihdrntov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxgjlxshm.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtwfvifvco.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtujfsddva.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gtkzcykhsu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gtjfxapfzp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gthievrjvp.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtuoforcbo.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtcdnbkxsq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmlquady.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gthxyfdkgf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcthfetbb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtclpshbyo.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtdsloovtl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtoltkuoqr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtapsyiuoi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczwwbyoi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtnhditbqf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtoozcrizo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtndnbmnax.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtyptabfgg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtvgtdptsp.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtaefgxsvp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtvujhxwew.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtpqpdnckm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gteeuukvry.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtdhiknowh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbvvdbmc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtzqwjntfo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtcuozuyeq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtybkreewz.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtashpxira.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtvxvpdiav.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtqobgjjmo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtjhwzxzbm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtilazzmvh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtnhzvoyqh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtpvlzpjev.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtimxuvcwv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtspewlmzz.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtoxovwtfj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gtalevwymh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtlcyvmhjo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtkvvmsyvg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtvvbmdizv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtfahobxpq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtuujigutk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtqlpzvzuz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gttuahdoiz.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtpvyahluk.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gtoeealbaj.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtghtbepge.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtkksiangw.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtaobvzkxb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtzdihedcb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiatsdid.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtffbageai.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtchevkxzz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtxjixnrfy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gttkxywndq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtjsrsjujf.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtpynetycv.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtieyqgcof.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtyrmeuzff.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtandtettp.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkrzjkls.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtzbojrzxp.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtzpbgltbp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtcmnjejbw.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtfffjiehs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtkwcypgws.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtkiqbyahb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbvvknkf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gtzoemyhnx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtqbxdrafj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtxcnbxclz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmcrvqrpm.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtaosmqkfx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtetodkycm.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gttfgydbsj.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtgsrfkunv.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtfqtxcpvx.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gthinkaiwt.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtonqwdimi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtesligigz.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gtjvonujza.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtauhlqpvy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtmymzdlzi.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtsrlkjpey.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtweewlbwr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaykgnucx.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtegvwzhki.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtguyeyjdd.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gturflsnfz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvrjlozs.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gteapgekvc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtovwtuanp.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtnbtzmozl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtsnevteen.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtlvwwuzxk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtjnahsfkw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtxfpbhtlv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtcyfbvwhj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gthmbqicin.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtfipkyksg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gttmcgygrg.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gtjgggzwtd.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtqjpiafqk.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gthvsglgzg.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtbpngtluv.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtpwwujhwp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoeqvxvu.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtspfmerbs.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtmkvpjatx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtmpuedhkx.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtdrzzobxo.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtjkgmjtts.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtwanskone.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtagsqnjtz.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgcpltst.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtgqcpqeuz.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtwhzvqdpv.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtqqhparmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtkxscnfpp.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtyauzqcro.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtwihugatv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtrcewadnv.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtmdcsiokg.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtoylhsmbg.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtcmvpewfv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtlsoyqxcz.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtxvdinviu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gttcjotwrh.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtqkizezgb.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtuwhdabwe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtxxuzfapg.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpvwlvmd.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtmvdwfmmh.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtknpkowzs.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtnzwohrzv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtvjtusvre.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtypyzrdws.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtnwmachaj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtygoipcex.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtoljhwpcx.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtxhhsrvnc.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtbqzaijha.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtmgekbdzx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtcbonrenh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtsydqxxyy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyxtqbid.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gticjjhptj.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtcpylhdas.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gteynufemw.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtkqpltjsr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqatymncw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtlnhssnsb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtumiowuxb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtvezutlkm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtpshucdzu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtakcflgfe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtnlnmqkug.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtrrcczswy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtzriiklcn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtwvqdkonn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gtzfwtzsht.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxkvbbva.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtsoabbzjg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gtvbebrqeb.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtstdilmxi.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtgrcmylsw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtbjtdrjjf.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtarjecizb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtzdzqbrop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtqhmqwimt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gthfhldgln.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtnphspikm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtcjcjjewc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtnklphcqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtoqgzojpm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtehcudluc.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gtdsowhggd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gthqfpxbdt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtqyjlvlyg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtevidsqix.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtyzoajxbr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtsxtwvskj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtdcknttut.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtzuhcbmyw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtdzvimoth.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtkwihzkjr.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtfsmfltvj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtcfvbupbb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtrcycjiut.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtsgecxqbc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtsdlhkbuj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gtyjfkdwqt.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtcejzzfsa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttarnchlz.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtoxwbakbk.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtnbpsgnkv.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtbfkjkses.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtroqbzaek.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtknoxkafe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtzghglcjp.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gthdtynhud.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouzxuygd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtjxkfadcr.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtbqrytxxi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gttyxuqzrk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gtegjukhvs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtbkmwvxtr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtitvnbdsc.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtkaocgnpk.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtvvxnuyhk.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtquafpbix.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtdfzrczdl.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtyoqiatpz.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtbsppshrl.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gtxxbkaznx.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtuoqrfixf.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtbkyhcski.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtyprffgkh.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtvfksqcta.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtgiltfoux.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtzyuajaim.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtdorjcxfv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtnqaerwbt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtgheekttp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtmzosixkg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtygvkygkh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtynxzplvx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gteuaijjxr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnqjiciy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtabelqfiy.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtgenulpnd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtrpajfrxs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gtegkjxtrp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtqddklsgg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlyywqkh.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtsvvhqggs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtrnbafegb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gtijxdxtry.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtsyyhnsqm.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtzlrgzpzg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gtrinupyup.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtujrggiut.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtoznqzdwj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtlvfwujsp.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gthhecxtna.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtgvlrilex.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtsswulsjz.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtfjnbqrhd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gthkguxzid.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtlxgosjho.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtxwpwdjwk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtbtnnjtgz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtyneepodn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtnqxqnoui.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtktfpammk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtwfwwfvac.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtlrvnnxnl.html


<!-- 参考信息 -->