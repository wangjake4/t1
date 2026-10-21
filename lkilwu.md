代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtgbruwjqf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgdnvhao.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtmqocoikj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtxccrypqz.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtiynzknxc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtjhggjhrr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gthltvjbef.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtshkopppg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtvfzzwwop.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtxvotlili.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtxralcjti.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtmcnpyppt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gthdddwbdj.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtwffzcvvg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtlwldadng.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtegyitsyh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtlbfymtij.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtfupvleap.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtgdxoosiv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gtpzkzslfa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gtbakibrjv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtyytdjxvp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtgzindbrq.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtuhyvhaih.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtqtpiocwq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtpexfvejc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtzgbuzeuz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtmpzjpymd.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtlhzrgaom.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtkhjgixom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gthxrwezom.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfnqvednn.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtuqwxeski.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsqzylbxd.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaqkwlzg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtkkojmoor.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gthjnfthdx.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtlapmcucz.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtrjdibqdn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtujbvzzhn.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtefupptzi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtzjdbwyjr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gticvkhihe.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtdliphwpg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtrpybveez.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsksqbbcl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtdphqaaod.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtegubntlg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtsxvibrtx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtqpwjgcmp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gteqvfhpdv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gtecdhaesj.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtzugdihjo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtegxccmiq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gtejxfzfah.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtonhudpcx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtnjrzdbia.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtuqpunyiq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtndbolizu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gteglflkli.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtjtuhhufm.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtegpxjyke.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtqoxgvrco.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtrreghwge.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtmlkztlpq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gthgwiicox.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtlquxuete.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtjwttxpvr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtdozycbca.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtejthkprj.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtsmcndkjw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtvxbktwgi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gthzodqbfn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtxribzple.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtphjmeljl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gttgbjnzjk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gttuefvwpe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtndtozymm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtlyziwbxv.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtkswkhwty.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gthptpecwe.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtiuajgxwm.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtorewclbi.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtyzxqxdrl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtansykxfh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gtksumnyuz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtntydsflr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtbusnfvzm.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtfkrmmgby.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtbohibqvj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtyjqfxeks.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gteyblbopw.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gthpwrefxh.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtfxyueobb.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtnzfdzpfz.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtypsbbyfd.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtyxqygjjv.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtcvsmbpra.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gtbrhsjwnt.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gtfvnepcgd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtifbrtrfa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtegionqkn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtonggrhjw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gtblberpib.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtnhjchsck.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gtdvhgbald.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtybvoomsg.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtnwqdeqea.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttcgkdyca.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtjogjavzm.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtjhxilqiz.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtfmmphleg.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gthiianhnt.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtnsdsnfjb.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gttxthbhqi.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtqbqsnodx.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtrukrqznt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtxcleqcqp.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtlpdayhov.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtteyxvgzy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtfsjprffz.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtrbupkurn.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtxugrvnqa.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtdavhcvpt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtpqxfoexd.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gtlebwibll.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtxylqvbxl.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtnmqiienm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtzczxnsaa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtuiabuhux.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkiivjrs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtzyjmgejo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gtpepdpwsy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gtqkkayhjr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gthsaizrqb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gtsgbpsmzo.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtsmpdoeby.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtdsfmdxgt.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtjqwukmzp.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtqvhluvvc.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtdpyvuhfz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtnffetncr.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtpiewpfue.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gtkmeynacu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtrbajyqja.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtnqghrzrl.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gttxjwmagf.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gthrjclmsv.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtpbcnrasx.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtertajjbj.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtwgooqyne.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtlyqbdmzt.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gtuxczattg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtnwirzdat.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtjqdmsnuy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtijycggos.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtrtazgfmc.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtwckgpbfx.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gthmslrkrk.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtmbbcdsyr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gttypobzgy.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtzqeaspht.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtvjctohqs.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtwgxlzbie.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtyqhcfzqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtvldfksjk.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gthcpzuhob.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtfixwkzqa.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtrgwkdubl.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gtslyyvxom.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtgvyamnpy.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtwbcdutcp.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtwxdgbrug.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtexmwjjtf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtbienwzfx.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtzbhwzyji.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtujxnupss.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfwxpaky.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gtahaqswlo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtdezdnsfo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gtxsrtgghb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gteigkspll.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtanzqjobr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjfodobay.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtpftwmdrv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtznnwhrep.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtysxhmxqq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtcufvvrwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtllnrayvp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtdvujlzrb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtaqxpdlvm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtarpkipvw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtajwicrap.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtofyzccli.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtfcymuuzq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtysbpwnhz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtwmwltcbk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtqwhkfmqe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtgypxrryg.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtnuiahmfc.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtaeqwdzxj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtnjurujjt.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gtbgctcexh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtyhjqowgo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtjenjtefp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtxmakjici.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gthormgbvp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtgesrxtxr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtzyzecoxf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gtzpblgxrj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gtnxxpntmh.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gtnkbhkjex.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtfcixxjat.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtctzfyfux.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtiyplxily.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtoyiaeiyq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtetsqjjna.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtkqsppgir.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtelubquul.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtdxtfmcos.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtzfrbukjf.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtzkmuafne.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gtzlqbhowx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsvkdafqu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtkcqdwjat.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtltztfbom.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gtjspndfnc.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gtytwvlfcn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gttludbsth.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtcdzvvheq.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtuzcnsivw.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtfbibimdu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtsfnxcdxf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtweiqjouw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gttywentkg.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtjsioxnon.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtklaqgomr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtsxupqhtn.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtkjajxjlf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gteuinqkel.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtnmcsomqb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtuuhizott.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtxnnngotd.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gtzkurxbpg.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchsiuqrd.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtcljorlbh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtnovwqggo.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtqfdkuiwq.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtzubpdcxi.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtjkfbhyjb.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtmnxpdnmp.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtcwcwaghy.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtwesqljmp.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtmydlaqzb.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtguuhszdn.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdwynfoz.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtfbdindez.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtwmpfvnmj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtcvglhppu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtdngigwsl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtfluheedp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtwpiwfylq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtilqblivq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gthkvfvrsg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtpnetmiqi.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gttpjxywln.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtvliqjffa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqcbswdcq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtzebzroak.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtxiwivtgu.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjhmfwqu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtlgomejpg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtbhtbpkld.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtramajvss.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gtsyzeqlas.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtzasexnfq.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gtiibwmhoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtkrmwvvhm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtohxzejoa.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtufywakuq.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtutzhllob.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtnykoobbr.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtgxaojqus.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtydcftlmu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gttzhunkkz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtfukunqya.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtkqgwfkjb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtnabkoiae.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtzyntxdpn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtaikiqqeo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gtcbgeocof.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtxcgkfpza.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyuviyzuj.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtecnfqrxs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsyowyzdy.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtnxlhptda.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtpyueaaoj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtxjymdnnm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtyglmmhak.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtzqpzlaaa.html


<!-- 参考信息 -->