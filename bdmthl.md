代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jonqgkrb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2oteshkcl.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2nkcdgzky.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2gxxjbqsx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gt2iscvufhn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2csjhqywu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2dxpuaczg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2bhmwokfm.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2dksqbctp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2edljyxzk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gt2trtruiso.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2euufvfzv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2icgfjvon.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2vqvjehwn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2nfcvejkw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2oopbzjjc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2gilruovy.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2ukfuzpwh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2apfyrwps.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gt2oxmruugi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2emdnqqdm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2sapffwze.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2pgfaiaco.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gt2kavkimym.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gt2sjhuoqae.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2zromcgjt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2pqyubkqp.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gt2bqgsuxsa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gt2rchuhwqh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gt2xlbrzynj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2bxvwqzgs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gt2guwpgwov.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gt2tncuxcin.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2dxlbtgts.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2tukedfpn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2gcxkkami.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2tupiuosw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dijwqlct.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvbccdpm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gt2wfhptieu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2qhujjxta.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2xciatspp.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgnfjhbx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2gqadwcrv.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2hrlubfbx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2jfknssbg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2mbhfjjdm.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2zkngtjja.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2bywridcz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gt2bjaqxewd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2mbqceqpx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2qwcciiqq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2oxluzpuq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gt2ptqxnwqt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gt2nbmmmhug.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gt2epsuhzko.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gt2yfcviwpv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2pmevmnhy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2mxoqitwz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2iatvkmhv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2ozpjcthq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gt2nzbmghlc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2edolldvi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vokobpnp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2eyuvnmxg.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gt2ykpgqvuc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2siquahla.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2woojcwzj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2vwhmjcbv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2xenchrlb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gt2pzcqrqts.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2evtbenoq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2oqzhydsx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gt2bsulvcqk.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2fatsacbb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gt2nmnhkiev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqxtitci.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2hxnsucip.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2wxyxuvwa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gt2izohrngv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gt2visbprnv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2patsykjh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfkplhha.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2avkoovgb.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2tmdxapvy.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2qmywghdt.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xowiuzxn.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzkpwcpr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2anlunlgn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2jcoflhhr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gt2oeyvblls.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2itiivirw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2ctgmwrmw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gt2dtbrbmcx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2sxmfmdow.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2acyatekc.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2olsoowrp.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gt2emdooxdp.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2lfznqexy.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2cqcerigl.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzatmxls.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gt2dcszemwt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gt2bcyazazg.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gt2advjlhga.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2iwliiqjy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgtibtxl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gt2sogjcbrb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gt2jqsfvlsj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljbdwook.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gt2rdbnjjek.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ecarnopk.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gt2ybjvqnqu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dnnsrlen.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lygpwbys.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nguxknnc.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gt2clufozmd.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2phvqqgfv.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2wyosbwsx.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2npbvromq.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2whkjpmeb.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2xpzosfuc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2tcveubpj.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2yolwmrvr.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2ddusgztu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2esubkqhe.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2arxvbltv.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gt2minovogl.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2yetdidtf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2ujgvocpf.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gt2smdtzvmu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yspzxhuy.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2dxvtffgv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2qxvwingc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gt2rqqfhmbp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2hwycshkw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gt2kgktrtzx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2kabdlogq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2mitwrpdu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2gddexebl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gt2cwzegjxh.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2mvjggqng.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2cybsctuy.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2byppmzph.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2ipassimv.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2llauohqy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmsdnvke.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2yqybwakp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2oatvkhng.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2nhvqqhdd.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gt2spcnzhaa.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2cfyeheau.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gt2mejzkfjx.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2leliggfj.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2cfgwgvfv.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2gwtbjyqa.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2bwsoyuqg.html

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gt2knyxsqib.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtjamexm.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2fjkxbvnc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2vhrnubmy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otxumvvp.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2fmoygwzo.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2jvdumprg.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhapreva.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2hdtqqbbc.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gt2fpltokkq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gt2dhqucsyq.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gt2odobcsjb.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gt2zhpgoicc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gt2rreydrvm.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2cbiqtyuk.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2xwjjhvvk.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itwpxquk.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2ojlkyefe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gt2usuhnukf.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gt2onjsvauk.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gt2qiwnnhgr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gt2vhwhiade.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2lujzmudp.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2cxeaosne.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2nwijzjks.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gt2onybpevk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gt2dlbhwsjo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2dosyitpb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2ntsgmlbc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pbxyptoc.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2bhawmiar.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gwvruggv.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gt2tyjnfbde.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2spfdhgzx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2xgfnroqc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2irutqpyn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2nnfjwfod.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2zwngkwwi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2ifosrqub.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gt2cikrcmxh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixiovkop.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnqajvkf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2hdtafrst.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gt2newxxrbc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2xqbbyspt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2pqtsvyvp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gt2axgeruan.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2jgttzucy.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gt2aeijcjjc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tamrdmto.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gt2sehpktau.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gt2rascojkt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2ermijnja.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2jbxanebm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2zrwlfyuz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhzdjmas.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gt2jfnjhrpt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gt2nocnxdks.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gt2rjpkkfdf.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gt2yyvqpsuf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2qhzvojux.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gt2gtafwtow.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2csfoauob.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2qznrmshp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2fenbervb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gt2gijfkjam.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2reoxqocd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2ucbakneg.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gt2aaeostjb.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2uxhxhqws.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2savizuhr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2gjrescya.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2swlhwacp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gt2zbkiuvxg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gt2hxnefmoe.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gt2rzzwguhf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2iabcetvn.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gt2zytlislo.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2cgahbhaz.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2gfujbsdk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2hjfzfigh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2lfiztapt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gt2frlxgmkt.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gt2njeskipm.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2cbufstfl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2ojdvlkoi.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gt2bepgctgz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gt2zuhiftlc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2vohowilj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2uvienzan.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gt2ogruukrd.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gt2isqltmeh.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gt2tkqfinir.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gt2grymgqza.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdbpcecq.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2eoczpyym.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2vbyjanbo.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gt2qewrhfpq.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2puiznjrs.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2mwduhjeu.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2lfciaaiq.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2vzyryjux.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2vytjdrwk.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2afrzfpqf.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gt2chhnosur.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2umersomh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2ghwgrxhl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2auhfoaxv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gt2yxbrbywx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2mehuxmnw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2gdewcwky.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2mdwihhvz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2redbkeqo.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gt2rbaeffzh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syshrfna.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2eahomcwm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gt2pkldjxfk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gt2vqazczse.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gt2voecoyra.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmsxheng.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkbcoxwx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gt2anfeggdy.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmrqgjnp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2gusbdykq.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gt2yqqpuciq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2sbfgbreg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2uzgorztx.html

Java: // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2nmlrpeva.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2ykmjvhlt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etjimzdx.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2tilxzpan.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gt2mlihaidn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gt2injkafwm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gt2helxipdx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2uoptthkg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2yzjttdbg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gt2hxzqkhgl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gt2jelwwzrs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gt2vxomudro.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2pphwqrkj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhsnrtva.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gt2akbuemio.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2nonhsoon.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gt2pkfkklxq.html


<!-- 参考信息 -->