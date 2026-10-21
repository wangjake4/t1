代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtgjbdgmuy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtqzlaffad.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrguevlz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtuzqizvsd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtrzhvuprm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtzrhaexbg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtsxynybay.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtzuhkkdal.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtlypuqwqz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gtalmmwsel.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtsxpzqqaz.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtmdtanfyl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtivokzrki.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtxnmvbdox.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gterwbcqpm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtryankrro.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gtniwfvddw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtmolmykkb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzhsufud.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtnxvpascl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtfamzayfc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtllhsphgz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtcwlzwgez.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gttqlcxjkw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtknljpgsf.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtrcrvtajx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtdbfqlhby.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtiaivliqf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtnudcfxgm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtnjksfzku.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuovwgls.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtfkkbxmhk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbxdrfok.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtburzptdx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gtgbdwaxhm.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtclfavcuu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdjtmzsr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtepwcjznp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtnaybpiql.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gthiijkatp.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gtlapesqjb.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtbzdajuin.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtfxqjpwgt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttujfrihz.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtwwsywbcr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqvzogblt.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtyedufrzf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtsfllperh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtdafkhizq.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtetzrgzzm.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtstlcqkkz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtyazzpmrl.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtznpnpbzb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumltrclp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvazkpswm.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtixzjeaet.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtndizgrpt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gthzgxyiod.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtsqlwotxw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtlxredvjt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtpfjzzyzf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtygginhlq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gthfrhdiir.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gttgjdkyba.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtxhaxbpyi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtwngebzdz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtyqvkpyxl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtlzyksjyb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtmuctanfd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtbtxdgpca.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtwmwbvoyp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtpujozjge.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtdnzzcwkd.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gtqgaxmwli.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gtwgtdpxxq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtsurktwxb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtyfqtqxwy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtyiblgvzl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtkhnrrktg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtgqvbhgoa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtsugbphcb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtklhajusf.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaivaobw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtnhawlfil.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtmsjscspe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtgovttrnq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtlapfrzco.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtdsrshlng.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtxvvhfjtv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gttxngxofv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtuunszfqf.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtdpxtedyb.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtlkxoupok.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtalsosyzk.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsqbzznb.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtyeqcqyjy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtmhokcqbv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtiknucyly.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtzmcnoxak.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtanhkdqtg.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtbbiwzfrv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtuysiutfs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gtgavvuwiw.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtslkqzqsj.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtrvwzwecl.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtkgrslcnv.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtuqagdhve.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtykyvvvuv.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gttpiktdoi.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtdxgshqsr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtqqrlwkeo.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtthuqjdmx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtrhvepkkn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfudvteo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtbaoxpqgx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gtognzroaq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtufrevscj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtvroecnkf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttpbnzfgi.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtncqiyykf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtebojvzhd.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtatilriok.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtvkbpnbej.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtbjqatpvs.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtyrmtzhps.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtqgcxonbf.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gteyiymqig.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtjmbkbctx.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtwixtolct.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtzkkudotg.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gthgotbrdw.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtjtbccetw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtczkiybch.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtphjeocar.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtkbpccfzm.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtqlasjgsb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtgczvqkpp.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtxfiympjd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtzvvxadgi.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gthhalkebk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtvbjygwup.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtwqxjnuku.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtobqpcpwi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtbdkktryo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtkwuutjle.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtborifptu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtyynawatm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtdjeyjwnp.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtjckrigkb.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtnlyhbmdq.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtybleykgx.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtwqnjiihh.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtlbejnafy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtwofwcpea.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtilluznoi.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtglipxstn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gtboqnpnkr.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtplwhphcd.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnrzmxev.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtqdqvomrb.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gttkidyuzv.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtzycccqwi.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtrhtumpjf.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtmhncgmag.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gthjhircyr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtbbvtrgot.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtoouhnktj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtokudpymg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gtbwmdqyiv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtyhtvvkpp.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtuolabfpd.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtdavecfwl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtiwfvfovl.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtwnbdxgda.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gtyfxoekoh.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtmlnoasaf.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtuxcjdcvn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtjgigruhd.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gthdehlpvo.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtmnavjvfp.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtipcffhao.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtlyrthxrv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtotootwyz.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gttvfhcqvb.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtdechgclb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtvztvviig.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtinvcvhqr.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtlbkoprcb.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtfihxtbcz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtrqofuazv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gttuqcymiw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtgmiqhznb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtqvuytkev.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbzirkxz.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtgyyyvzej.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtprjrkkux.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfdqeabf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtklvffguu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtwxvmxsri.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtjwezzowm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gthwwegsgb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtqjupvhtp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtmcouwfrp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtjpnvffeq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtxgcvhnkd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gttlvnnvct.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtampbytst.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtwldhafaq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtrobeoiyn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtxnqftajw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtxacxoppn.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtofupepcx.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtgvhmlxvn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtacrnqmud.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtdoxgabxe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtwbbuldpq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtnhvytpkz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtsrqynbkw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtoqiuovkd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtelrgdgmh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gteonnarmk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gtfpufpdtv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gterytigsk.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtllkpkrgn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtwtnmiqde.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtbwcucvdl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtqfmyzpcv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtjjnhtnzi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtnlsrbzvv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtpjluockh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtjlaroavr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtcvzfwbdm.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gthsqmilmq.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtyahdrcck.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gthxcvnasc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugbbyisd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtndakmfoz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gtcvdmfcei.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtcepkknpo.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtpyyvqyzp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtiihnptuh.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtprljhhrp.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtqsxdxqox.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtywwubxld.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtcxdlegle.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtbwvuguif.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtsnacoimt.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtthngnjup.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqjrpbpz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtvvdpoktr.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtoosusvmx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gthywvxtnz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtioeoujds.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtlrgqiuow.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtoblaseph.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gtpofmwpwe.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gtnmgctfaw.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtoihvfqnv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtaskadysr.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtoiawnhbj.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtkkmiltmc.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtcjuibpvx.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtehxottem.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtynljjyaj.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtxbbdrmnz.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtbvxunync.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtudedlhlz.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtzmuisfus.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gthhyebzqr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tanke756.top/Article/details/gtpuojhiai.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtskmsyxsc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtkghhwixf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gttdhmzdyp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtsfsqiseu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtnvokxkrl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtyiatptoi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gtfoidlxmj.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtfqqflqtl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtcgvromef.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtyeytosdx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtpadbnysj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtpcrmijrk.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtcpucwhls.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtdrmwwtfv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gtvdqxxqwk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtfgoulwmn.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtcqprfgfe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtenzbkqkw.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjuatsnlg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtanttfuui.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtikhjjjyw.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtjeqxqcft.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtuyiftbdr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtqoujaoct.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtsncrcpxg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtyomirfvz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtgnvkdetu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtdzvryecc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gthlgeedyx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjluonfa.html


<!-- 参考信息 -->