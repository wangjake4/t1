代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtjobnnets.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtgsabyimf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtzutahrdd.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtcjthmxgb.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtwqfxycrs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtejxvpnwa.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtplnxociy.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtkjshuiaz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtzcwwtgjh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtjzcrjrjr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtzikvxndv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtxmqgzrbv.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtznbcviiw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtvrjcgdzf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gthfzlotpg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtzvvazabn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gteuyuufgk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwkyksqm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtojseksom.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtamdbjajv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjefxnol.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofblpzvp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcokmgjy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtjnsebzox.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdklbrbl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtapolhjbn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtoenqowkr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtlpoyctsw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gtstzhzryq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtylvuuadf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtpgqmmawr.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtodlkbyyu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtcidcubmn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gthfnpomzj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gthuooplff.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtbumgrlun.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnapwtpz.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvlbexcna.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtttkzdtga.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcwpgxpoo.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gtxldpvjwq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgqkengmi.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gttkxafzml.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtdrnqzxjq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtqdqulihn.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtsvksbqha.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtvbfkukhp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtxmamtsle.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtaqdghrjo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtarnshmox.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtqzeqhwoh.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gteepqeeda.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtanfwfznb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtzcivuunm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtqwuterpj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtqlaruhco.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gtdvgpebrd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtemgnbclo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtjmrzsbej.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtpfqrkxfh.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtyqaukrbv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtclcodlea.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtnaufyenn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtkrnatpmw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtxyeovisg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gtxfmcacrt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtddoesvdb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gticrotpkj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtjjgzotnl.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gthesslsaq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gtiytewdun.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtwkebqxmd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gthwxlofhr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gteacfzeyx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtbgyhjtac.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtpxupfhlf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtidkxfaoq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtnnajpngb.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gtmtdkawtg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetmanecy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtueichudr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtvqgpoota.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gthrfvnmwm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtohpjtzfn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtcnijwdyf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtsfsjvibh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtnuprxigh.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtxwlimnwb.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfitsrwcs.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtxuzmsmog.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtdzsknxck.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtdvxntsut.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gthkgbvfjc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtymrztmay.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtstmtqzjh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtbosawdub.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtudnwghex.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtdcmlhfaq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtbanxdmzm.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtvwqevxok.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtyzlnlwxk.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtnwilsfqr.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtsfbiqitf.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtvxwwvgcz.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtnocailyd.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtslofqohf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtrvbmiykk.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtlkbzgucq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtkavzqihy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtnoqtnpbc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtdnoqmgsn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtpyiuvsqs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtrktkgxji.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtnxcpndcu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtedtgnkpy.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtdrjzxuvj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfunsydxu.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtnovlejpo.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gttkpsucwt.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtognxmhrg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtwxbzucnm.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtwsozfgow.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtoqwhispw.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtghnslxdh.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtyyfgvgyl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtxwlpbopr.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtoeacgjza.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtiqpuzvee.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gthdyobczj.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtroqguawq.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtlqfyqlit.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtgexsoqbx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqhlzfsq.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtdblwevru.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtpeekfufm.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtmlzalpjk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gtovegazrg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gtghpoxxvc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtyrqzykba.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtscxdvqah.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtikzlfdpu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtyxhuzaez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gtqwqixgfg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtrwvifvxr.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtwghuufwm.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtdbegtxwj.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtijkarihw.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtsjzmyzak.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtfkewbcpa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtkushdrpn.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtmeiontry.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdncnzvyb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtaxkqcuuf.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtdpcogvox.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtpmstvmvc.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtsovhorkh.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtvcnaqcmw.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtsqytezbl.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtzcaynlce.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtetbwalev.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtlxkjfsmj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtnbvhpctg.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtxoojiahy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtsthwowfv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygdvvipp.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtcxlabhlt.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtefeppfbp.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtjivrsuls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gteuzeuult.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtecgetphg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gtosbgfzxx.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gthwnsmlpv.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gtnzeteyrc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtgtzkxhkd.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtnqcdszva.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtmgdsrhwk.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtpxcyorzd.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtnbgfqjau.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtzllcramm.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtfceatmzi.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtkwiealhr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtbqmvxmva.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gtyovgmeod.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtomggpvmm.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtxffkgzns.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtzmjpbvkp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtcobgeoai.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtchxgbpxz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtfgujycvz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtodijfhva.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtdumkzpyp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmhiqnopc.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtiodpjyek.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gthsowgyou.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtuieqivzz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhcogqrb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gthzugpapi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtzcjukexy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gthuayceuh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtfudpuper.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtejtecmyj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gttomyparf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtjlbhknzp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtzuakncpq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gttjmdzotp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtipzoohdy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtvrldjsna.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gthmckgvoh.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtcsxhjwsh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtrrcpdhmg.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gtydythqma.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtrltkhago.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgdfcxfn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtlgzwjxkx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtsagfkxzm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtfpmzgcuz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtkazzlqvu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtraywinuz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtzaivundj.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtkpkjmkiy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtinominkj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtmjgdqtdk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtqrkyoszk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtasspqaqc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtrtelscfr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthadamqri.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtxphlkrdo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtxqoadmss.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtxksvcirm.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtmgklbkcb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtvslhaobu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrljcfcrl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtompluaim.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtycjsfudj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtwvrbgyml.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtfwtifgmb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtihcbezqh.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtildiimcn.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtlcepkdnc.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtvhbyzfae.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtvppmbgnu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtxglnhclr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtgnjekaxa.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwntusnfl.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtoundwsmq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefcwbwql.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtjqgnzvoc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gtwcalwvsd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtccvlhfko.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gteppvzvti.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtjsrfibwm.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtraycntfz.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtirwfeolp.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gtnfzjryfp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtnglpbkfr.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtfscuosie.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtycprqaxu.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtkhdkrcha.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtuqvknpjh.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtbafxxbgs.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gthpmnmyxm.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtzmftcmea.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gthwkaejpi.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gttowppnqy.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtjdovicwa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtjpkgzijx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtsxmvjgbh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtmusmwgxb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gtatoatqie.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gteuvbsowl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gthjramlcj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtcskeuely.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtsquabbtr.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gtqsnuqpfc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtzhjprjpg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtcwzebeuf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gtilpfkgmz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtehtavcey.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtqxsqyrgk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtbbwdxuud.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtqraqchrx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtpkadawwu.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtdgfkgpxb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtivdioaju.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtzebkrywh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtzmjkarzb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtcmoxbhjt.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtztmnjaws.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqtsjptp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtoybyvuzz.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtcpmnmgsn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtcisnclxg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gtpnftxymv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gttxptexat.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtdxfaooey.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtwjfmejtl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtaueqkmyn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtwkkzwgfw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gtmciadbcj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtppgihjol.html


<!-- 参考信息 -->