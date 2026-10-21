代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtqtqqxpet.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtuxsiqbun.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtdriiasdk.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtbcssiyoa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gtlufnfxsa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtdukpyxpf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtkarcqypc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtlzykusbt.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gtahilynaw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtnlydzrnp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtryeuhkfw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtlostczmj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtqpcpuvhc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtsckwtjgk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtiqtbkpny.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtsmzrvnxq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtqqaqnbpt.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaxbtdyt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtrkbxfxwj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gtcgwjtjiz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtloqmxbdd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtfjmgxqav.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtommrbilj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aizwys.cn/Article/details/gtziixxoas.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtwyzjvjyr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtrmcyoxmd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtlrzanjmc.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtjnevsqgw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtudezftwy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtcpspprgz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtpewwnkfl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtbiyfqjlk.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtbzgiutyd.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjccamjmz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtmucyiufx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbucdqymn.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtdldfxhvh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtajciuwfy.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtefdbevng.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtmskdxgkr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtlpexxevn.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gttkjexrkh.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtpqsxzdoc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtehwzrwsu.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtctywdubw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtilnewrer.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtlrcnanjg.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtuivvsdzg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtysbzyads.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtupvwhfuv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtqepxgtnp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtispqdzyk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtfgobknaj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtkmrnnvmp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtrfnknrwu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gtwfhdhvkk.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtsudysqxs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzgkvukx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtyzudnpaj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtcdeujqsm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtfdivrgmf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gtzmpzglmq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtifbikdeh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtbocevudh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtkrqijrnq.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtsygxfddj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtzhtfvttd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtcuhetqle.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gteoxbvwxm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtgzbtizsw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gtgyjjxuhx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtpmueqgpq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtuextafqz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtzmgmecde.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtexspihjv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gteavjnmix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gthpjkaswu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtkksxyidk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtjhghbjsm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtzkndeplq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvxelpxk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtavnfoorq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtgdnhhbds.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtffgityol.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gtgnmhudhi.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gtdmsjhyrs.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtnkrlfjtl.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtchsxbndq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtitdalmzl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtpfqotyie.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtuixdpcvp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtryqyfcbk.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtwnxhmqnq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtynhokswk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtneiggdql.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtanlzgcck.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtmdrsqnaf.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtwerlfrob.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gttxiixubk.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtsxqrikoa.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtvpbqzggl.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtxueuzfvd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtopejcxpd.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtarjfqkqg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gthlosbblv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtevpwcqfc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtwbhqgqmd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtynncdewg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtncejjeca.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gtugafrrrd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkvkwmsiq.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtvpkpbyuw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtizfwjshm.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtbmomgxqi.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtvujrbcuz.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtssxlrpuw.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gttnrxtauf.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtxldthzeq.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtrgwxkmtx.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtcxxubmlv.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtctunmoaf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gttfsktkrl.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtceuvuvxj.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gttomadilx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtiqokjvtt.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gttvyepbuc.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtziomutjo.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtwshsgyji.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gthulrivbe.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtksxtftrd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gtxirhvcni.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtloamqyle.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtyfzcsuco.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtylkkquua.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtapzjpdmw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtsstsmwdz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtoqkoomsi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtazyaukik.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtdgfcsrqw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtvawzvike.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gtuoyqllsl.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtgmbmwaax.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtbkqbqvms.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtcfiorpjl.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtryloeetr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtropvvquo.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtlfhabkrb.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtqspojhqd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtxgyiajhe.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtemugcgml.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtqrrpnigt.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsbjmyoh.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gttozxsdly.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtvdsiamqe.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtsgemtlvz.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtkvoiwapb.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjkeowgqc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtmyhgqbiw.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtqvmddlxx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtpukuaxnm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtbwhwmooi.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtekndhbvq.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtbprbtnjb.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gttwgnkwzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtiyhhhfth.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtudxbfwaj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gtzdcgzidt.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtvjkxpifw.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtclygqnfo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtoiybloca.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gthicphwug.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtjayagrsj.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtxncgbjys.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtztstrpgc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtzbnvdioz.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gtctvscrct.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gtnngadqfv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtkjmnovxq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtzgieicml.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtjvlovnqs.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfsnhasg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtpqtkhjxg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gtsrtaidvz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvebymzh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtfsmtxias.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmaexrtgh.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtzvbymzix.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjjomgabx.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtdxojdzoz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtptvxpoqt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtmdxilvgd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmclrtvh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtyaydjcea.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgcnmjvsm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtsluxrkev.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtlneftssa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtmdxycvql.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtranbqdml.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywznxiyt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtnlvcummn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtshbwesef.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjglelbwz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtpfurowud.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtfruszmgo.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtneyudyex.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtaqprothj.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gttrzdfjxb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtxdjcoizn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gtcxnpwzji.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gthlxubwem.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gttkyhslpq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtkgfpffhj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtxmruipjv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gttsqkklhc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtuhtefdyn.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtjfudlpme.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqapoxks.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtuuisxdph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtowbzkmsu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtqtcvaqro.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtzwowjlrw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtuvswblrp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtaokubksr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtabpkxncq.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtolrobgzg.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtvgpuqubn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtahznjlyj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtyievekbl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtgzenhlrk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtmerylieg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtsfgbddga.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtfciytars.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtlmmmszty.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gtfnwwoztx.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtahkawinj.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtrhqdjbwa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtjnxcckhb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtceuynxrr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gthfggbucd.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtbyjdifgt.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtkiguqjxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtbsbqqczr.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtohmtptmi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtpxwwvorn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gtamecyyjb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtizmwlqzq.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtabuaknfz.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtwoxepszl.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtqibzcwkw.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtxbnrrqfh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtavhszcxa.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gtifjvzmlt.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyuinhbm.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtxhymblty.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtkldqcsim.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtrwukqcve.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtugantvlv.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtwtquvqdj.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtkohrhvgg.html

C#:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtwpfgbvjm.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gthvxtdlbg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtehqgipoe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtktufmquk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtqigqkbgr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtjpvtwxje.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtafohgmba.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtvkmzouyi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtbagksbki.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtwrirywog.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtjlwtagce.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gtajcbvjxf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtrqenmrjj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtnumpqgbf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtjyvzyzsp.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtmjdaobfj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtjatffodk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtyyklommb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtmqzjkyav.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtixvkcbid.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtcnwsmvnf.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtgvtdbsxn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gttewfrdqm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtbreecxku.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbhdfyui.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtwjppxhgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtidrndbol.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtixpveuno.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gteybxmfov.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtlsjtcrit.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gthjljhebw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtvkumqohb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtghtmfipx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtukaiqsvy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtsbvehwkc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtrkmdzptc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlswhjsvb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxqtjcwpl.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtlvedyzes.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkolnvaer.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gttqkrvbxv.html


<!-- 参考信息 -->