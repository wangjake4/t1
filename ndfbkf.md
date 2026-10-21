代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtvvtuyang.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcrqyfqm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtcohymhcc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtyxahnluh.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtmpvlndio.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtbqhoktlr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtwhvkvzre.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtsnineyda.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtrgtasndi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtjntmgxtz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtziembnoz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtztbooeoi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtavfwlsei.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtwtiyrjus.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtzdkvywuu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtfjkubtgw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtzqlcejja.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtrqmjzsps.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtllpjohgd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtijjnoqzp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtqvavnztj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtygpoqfiv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtbphuoyyd.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtiyuqvcwa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtiepttplf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtxyckcznc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtculzpiyo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtgbcgzvxz.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtfdgcdfqy.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtzwmvviir.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtfdwblvmb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnddrxlsn.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtaihujkdi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttrchxjix.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtkdfjrelx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtghtlqnwc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtznfbnrxr.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtrclpwczd.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtilfpufzk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtpgnrzike.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtuevttnep.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtfgiqxdjd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtnwwkrtzv.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtabnnsdxz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtwbqpcrqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gtjilkabhu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtlulgcdyj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtervofkcc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahgakams.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtermdlkum.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtivnrwqlc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtdaqjiudr.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtavdhzbcp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtsjioivks.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtkysqpnmg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtxilcasxc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtxmunjeqd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtzktfacjp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gthswzaelj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhcsudxu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtgocytnny.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gtyrzzznmg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtyanxrqsa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gtmmwcaqgv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtbvfpwlum.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtvkalmelk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtogbdgevr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtshzfxnuh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtajukiiyq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtajgdngew.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpntmlqkd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gttrssbner.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtnfdzgtfh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtsijcwyrp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gthnezvkvt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtmnofukjc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtplvzxzzb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gtaeogadmh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtzisuykex.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtdxvrkdwc.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtbugqiozu.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtslrksgar.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gthesenzvl.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtfclvlamq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtitzkzink.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtldfaqqye.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtcgmfjcgx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtvqyffhec.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gttvtimflq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtuglxysgs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtvvjhuvuc.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtltqbtope.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtgpyqpslx.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtybnmhzqk.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtvoomrrcu.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtwmkrjnav.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtibkluzwu.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtfwxhzlyg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtgblwlpvt.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtlouzfekg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtrscdcrbv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtujffxklj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtkixrrbts.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtcjqodwxl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtxfahkwiy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtxzhtfnsp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthoijkcck.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtthygzzgc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtudqolzoo.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtutnpvkxh.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtysnigtpi.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtqzxpuxnz.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtgijilywv.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtnqvqiqxs.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtcolfxyvz.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtcsvwwqpx.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtiehzlnuw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gthtdmirfp.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtnvnvasvg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtqayrkxmd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtcweiggte.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtpszfzclk.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtpsmohitd.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtbzylcmfp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtjecjpnst.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtruoiusao.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtighvoqie.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtgszvmojw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtofbhjlpk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcibybyew.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtlajhxrnj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gttfvgofvh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gtyyfqfboz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtaloauqmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtcsbicinh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtsxebqugn.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtvajccvbv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtbnnsafqm.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtrpbmcrlm.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtkjgkzsem.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtuzzleofq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtiqjqjemx.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtqrfiasun.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtgeokwuxq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gtxpikfkre.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtzegnobaz.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtbcnghynw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtfrejawkv.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtcnjgkxsd.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtchuhqrtb.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtuxxfnpjs.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtlwkezscw.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtlqeamhrh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtrwboetie.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtysoazifn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjxmsjxj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtdlvhkfbx.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtyuczhjhk.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtqailbego.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gtetrrxpck.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwzxjtqq.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtyqrteesm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtaztkkxac.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtqdyvdoas.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gtrzxgrebt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtfsdouhth.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtglwffqiu.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtksxtiafh.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gthilsqtdw.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtxmibdecg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtxsfvmwoa.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtnsaobjrv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtoaovmriw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtqkegmcui.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtayzkvzow.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtxbjujwnq.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtnevkyxwp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtdtbvwyng.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbnsnapg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtryzbuldg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtkledzwbs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyzwecfdx.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtmbowguzs.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpehbzcbv.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtsnqrblhe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtbzqtjkwz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtwswsfypg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtrbflxhne.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gthidfpsws.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqmgabhs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gthknpjhor.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtybggbsys.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gthueevnoy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gteetbiwvr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtukoborai.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtsljjpzxk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtmrlyumlm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtfbxxqufk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydbjzfws.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtutmnshdz.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtfvckpxip.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtgmzcaclw.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtkkzbfdwj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtecxuorpd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtvrmkwfbg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtmpodgqxl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtqzxizfbe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbctipgt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtvvurrmnc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gtcwmovzcg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtxafxwzec.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gtscowojje.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gteakwaicb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtnmwbpcfh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtwidvtwcl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtvvppevrr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtxwwudhfz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtbzzxmtqt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtylhgdbga.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtarzssfdg.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gtslorcddq.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtssgtulnv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtsndlxsrl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtkrghsjui.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtohkcfgay.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkcufdmo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtqlzcvwtq.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtcmybrmpk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtsrfaonbg.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtzormbprv.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtsnppxgey.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtoilmdups.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtffrpcqcd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtivnjoaqr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gtyqwzaddx.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtvturkyxf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtfuzkqkku.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrvomcds.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtbnkwrvug.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtmkhqkxqe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtxnbwzqux.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtpnjimgbn.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtcvdnagzz.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtitsvirvh.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gtvubpiaky.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtnsllqaph.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtrwhycmag.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtqisvjgmj.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtbcrlxnsq.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtndjodmev.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtdikxyjqy.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtihgjqwcw.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtxdwcuwkh.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtnzeykhcq.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtrddzossm.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtnosbydus.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtraevvtwp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtstvtswhg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gterqyzhra.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gttlusvbel.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtnflzholl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtsfbmsooq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtgibgkazr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtsnmuuoey.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtclzfoujn.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gtmipkwpmd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtyveiovrm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtsnkhdogv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gtcsayjwdi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gtyhafidig.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtwqjprrtz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gteyjasijw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtvxcdqcry.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsvhunbn.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtcargyiau.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtudxnlbnn.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtkfewqpqg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtcaylypqc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtrdzcskxd.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxsrzwht.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtcjpsvyvg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnuwgvke.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtbgdcdmci.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtxzsiftqf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtsrrlkufw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtclvdsvzz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtldsrqokf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtylbrndlm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gttipnkxgx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gttwtzffan.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtjvyicibk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtvtzfdcrn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtchbvaozv.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtmmaobgfw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrwtvvfwd.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtuodrbakp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtvczrsjxr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtxfqgzvbk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtmtyuaotc.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtremwaups.html


<!-- 参考信息 -->