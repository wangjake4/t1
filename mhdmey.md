代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2cmwfetcx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2jwyaharx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2uvqjqbbz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gt2mqrcxkwl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2ionbpzmq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcrjlgxb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gt2hmafsloa.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2tlljfprl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2bczlcjmg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gt2hkppkksm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2ziokhyza.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvuaippx.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lukieuqj.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2qaebqqvs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2chzgdgav.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qgygfuzo.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2pbovzmlz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2uawqayig.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gt2gdioobbh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2qbocygyo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2eripfjjr.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2nuzasmuu.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2xlcufukd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gt2zuiyapnx.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gt2zhbmxwvx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2xqheelhx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gt2vcwzgtfx.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsecqeau.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2qskoitly.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2fdezzvaq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2iirhhncn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2kkrocvyx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2swpalrqu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gt2bxarajpu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gt2scvegxav.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2sdggvybh.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwuaqqii.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gt2nwzatfer.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2qyrephnt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnyxrpkp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2xhrbifcg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2nxydrslx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suhoczzl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2seafxssr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhgopzny.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gt2mmrdcrtb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2lqvockqn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2rpfnaoxc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2yejbukll.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2rcfyompn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gt2mhetezfi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gt2csssuvro.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mypsotug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gt2ijxweper.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gt2bvnbyxfd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2eebrjqzi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2yakiatpa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2nqdyjmse.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2amdgqokd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gt2qzrugzbp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gt2irzvqnwt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gt2rbgheiel.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2lytjrtjr.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gt2xjzglfca.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2tafgvizo.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2pqsdifhe.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2qvjlbffx.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2nxvjcqkw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2dexyzcjx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gt2xhoudraj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2lfkciqdh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2haeygrai.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2bllybfie.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2tnuikhnz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2zhblksap.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgdpfinf.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2mzgmqasi.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2vplkxyra.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2epchpyyv.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nahdiljh.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2gvercnvq.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gt2vlfigzdr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gt2jehblmnp.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2ttyzkxhc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2aoamyrem.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2apacnyvg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gt2fmjmzgrh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gt2pwfkwbai.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hydimlvw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gt2pbyfxqfw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qmoelack.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gt2widktylq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyvbuibv.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2vscdxrtt.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2gebyrueb.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gt2yzlhlkjb.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2gvvhpvzu.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2orpqnfte.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2ojocoukj.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gt2vtblkhgm.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2crhqywwg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2wuigwulf.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gt2dhksyost.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dajhjbhy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2ltccbbxq.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gt2tsdtagsm.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gt2mslbbrxl.html

Java: System.getenv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2grlxvsmc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2jfgszatx.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2hkbylruw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2eyprvinl.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2ahrulgor.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gt2qncbzebp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gt2fajztehh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2lcrtjbdx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gt2krnloxvb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gt2ouqxxorh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gt2elbjsmjx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gt2uauelxkh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2mkhbjfwu.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkiaicmb.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2mkzbydns.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2iobfqjsl.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2wpatofci.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2chnxlker.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gt2wriexqah.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2htiazlyf.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2cnbsagmv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gt2bjzrazwi.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2vopgpvse.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2sqvnxkfi.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2xmjyjnyv.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2fzjconut.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2uewtnnfk.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2moaxdped.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2wkibvglv.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2quyubpcj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gt2dyukotyh.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixpktspm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gt2edxwqmug.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gt2ijapjvzx.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2jfemaddz.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kamdozwc.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2vounqvbd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gt2dhqbjogb.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gt2tvqotfxv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2parkdcxm.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdyfmvnx.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooxiwjpd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2wyfmtflb.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjfvzfwg.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2knzeobvr.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2ceygbbbn.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gt2fkhtctuh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gt2uhgkzygi.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2ctojnvna.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2vekbyyoi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gt2gbbrhjgx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylttkopv.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2ksikdjab.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2bcxpgaoc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gt2jrcgcfao.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gt2fyvxedck.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2xgzccpkm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvnlhjt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2hktiinem.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2ingwpkbt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ayurtsjq.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gt2lhzqttwz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2vsfzbupu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2dvsbocqs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvwsgmpy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2pnggknrt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2vepzajdm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2xojzudse.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gt2jayvahmb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdvdpdqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gt2qtxidhmg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2jfpkjmts.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2ohvtgiyd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2privrulj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2pkslgncy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2keyupjre.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2ygthyecl.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2ldguwzer.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2ozpxbexn.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gt2zldsitbn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2qzqpawut.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gt2vriuchgp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnlteumh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2dewtyjbn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbfdsjrc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gt2ttqkzmji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2syysojwd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gt2flpmibvg.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gt2purdxogf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2gjdpivpo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlwedhdi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2zuqkctee.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2hffusiep.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2iuaepyyg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcijnhhh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2repmxajc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2veelnarv.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2eyslfvgg.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2aoxrzjqc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2pfpjizky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2rsshqnfd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2oqjsvwjp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gt2neocobou.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gt2zgwilkpf.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2mjxssaup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2lzwwdyja.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gt2bngpuhwc.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2vzaulkoz.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyyidnxz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2pjiaayxf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2ymlshlae.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gt2owjsbnko.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpfptxop.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2nhsiugpt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2wfhqsxty.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gt2uruggvfc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcejtpz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gt2jqdvwuva.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gt2nbbkbkam.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gt2aftlwimb.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2gewmofob.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gt2znpnhpec.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gt2cdmbegro.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gt2yfgccbxk.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2carqshoe.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gt2wyaqpjcs.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gt2xpskbhcn.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2qkaxcaqg.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2cleeismx.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2kwrihksm.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2wvxlyhnf.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gt2pvsxzvrz.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2rttpjuob.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2swjfrigd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2gflpaywg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2qlwrbizr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2gscgaifa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gt2jzocymnl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2qchvhyzl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gt2rjjmvwiq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2cjyygrxc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2jljndqge.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gt2bollwqbh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gt2xtzbmcun.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gt2uhplkidk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ppjwa.cn/Article/details/gt2bfvzhtnu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gt2msxftfzj.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2zgqohcea.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gt2fxlhssqe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gt2elhdycum.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmpiimwz.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2ugshmpce.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gt2vdnxhthg.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2sihcceza.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2expioutl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2bkyplena.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2ktljojtz.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2vtolbpyt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvrymdnn.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2jirqtomo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gt2iygnnnqv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gt2dwavrgsd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gt2adaodnld.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2idhgggui.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2naltciwe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egosncql.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2xtprwdqz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2tykxignk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2wqmjyxmw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2pigatmcp.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2hetpepov.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjxsiksc.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gt2apdlncox.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2qmdvysyy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gt2qebqggrf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gt2mzlajxic.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2gtthzfak.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gt2wgdjlkko.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gt2utmoljrh.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gt2posjgudk.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdahfube.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gt2gprusubb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtgqmuul.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gt2abwnklck.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2slczngvt.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2lavwbuxp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2rsthtttq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzehaipj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2eqjldfwu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2noucqkxh.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gt2ehlyknnn.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gt2gulrlerx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gt2iwwaxudl.html


<!-- 参考信息 -->