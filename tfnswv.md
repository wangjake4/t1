代发 wailian999

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtlsobypua.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtposnanud.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtesnyyjcs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtclxamvpz.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gtmynjvvez.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwibwsozb.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtwdtupglc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gtiqheakjn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtovgbepor.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtxsjcjdvn.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gttxslkuva.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtkosncrsq.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gtxdmzefbm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtsemrxjpl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtmswywonm.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtkbflcfwi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtdvjrvbha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gttesnugth.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtlghcikac.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtxddstjsf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gttgnsxdxl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gthfxjpxoe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtkhdyglxs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtbenuorfl.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtbcnfzdpu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtsfjfewex.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gtvlhbqvzu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtrgdmlwao.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtwzpmptab.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtenmrnbjw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtshqqqfwd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtkxhegfwo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtzdzylzyh.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtzzgdodxw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtoolqfjhj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutxsdwbv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtrpkyommc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmuxiejt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtjgsqkrra.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtkemhzaev.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtihhbboaz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhnbicun.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtdmpweetk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtwtnciksy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtkeoetltx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtpyvduflj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtvpepivru.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtcikjyxgu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtfbpseseh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtxihagnbl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtaiwqxmhm.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtaldbxzps.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqoerybk.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gtvzwwiwia.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gthhunuyyu.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtnowosolv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtmhibdhex.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtbhcdnfxl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtltyaawwk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtvudhdiwr.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtlrhzxmow.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtuzavaflh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtvuaaltco.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtygugbssi.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtalztvvol.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtmrvlyweb.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtzxkadmuh.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtceqeiqix.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtklbanolc.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtvtwzseja.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtdmnmfpjx.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtlymjygwy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtrwwvzbzi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtdjkvupja.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtjeccrxwf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtmojgihuq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gthmtbafwb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtsmgjvdbp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtizakzphi.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtilxrijaa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmwehzlrd.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtnbcjtotw.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtpulsfzhv.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkfpspzm.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtlltttlyl.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtqhngkvlq.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtbkfcmjtg.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtonvtmbaj.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtttdqyjrg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtkatxvtwc.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtkhsmprxs.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtusnhpisc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtvqqypizg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtelmcdukf.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtyicinlxs.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtqjsrbmen.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtgiusgdta.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtwdtwozpz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtyhgolvub.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtkccaadbs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gtrhiudmez.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbofauvs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstlgrmfz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtohxhykmz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtdjmjptxk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtwwwstslr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtjhtvejbx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtduuhgxes.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtkjgvtmvf.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtdfuhwuvr.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtgekyrwcj.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtdvgazpcf.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtxtnggols.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtbbkypjza.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gteovbiumi.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtaszituct.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtaocrdqlg.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtaahhczjt.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtjcaximkr.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtjagsqmqk.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtnebteemx.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtkrgrwtiz.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbusqeoaz.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtxczlqjsv.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gttivwdzbc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtztdyzzhv.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzzlmecw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtrtjujchg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gtecieebys.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtkrecbffv.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtfhqrohcb.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtpkkokomv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gthvooskld.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtnbkmnofl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtakqhvfls.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtwntdctio.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtqzgnmzyr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtgetcyokq.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtfaglesxs.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtjfpyszvu.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtogbyfiyt.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtqucohwpn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtzqkfdjkg.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtvxeczfes.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtddovpleg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gttpmihwml.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gttsocobpa.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtezuxxssw.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtdvqyhsgw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtgcmsphkt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtmkvygyou.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtbwpyddyv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtsdpqehdq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuzilejcz.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtapmetlgr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvalcpemt.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtemvyltua.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtxwrjhapf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gthtklldak.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtfrrefbro.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtjfxxkzbe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtcqpbogub.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtdgqharhx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtjnjvketa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtekljdfvf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdsceazq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtmocypday.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtselesame.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtlypqfsqe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtobkaeppk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtfgmoesro.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtdakcnoae.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtbscpuzft.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtacxowraa.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtntjlccje.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtuyfsgrlb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtchkymltv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtjkkqhsxe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gttcbydgna.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtcocopopt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtzpsgzxks.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtzubcqtba.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gtnvrigtvb.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtqdnpttlm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtewydscjp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtupimbmcd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtetwflreo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtywqoesxh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtdbevvo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtxalsyvkl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsbflskow.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtknkgmepr.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkpqyzmu.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtsjvmqelh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gtbijwweuj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtonvogeoz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtjxegqcsc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtocmplurf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtxauombie.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtaglwndss.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtanesmune.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gthmaklrtc.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtwlnpromp.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtuyhlxrpf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtswluegdm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtnmtbrslb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtxvenwzha.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtpcmjieom.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtnqywgbrl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtawfvbdwt.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtfpgjuarm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtjsyimvaa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtiruovqhb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtlkavgahc.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtuvyniwae.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtaublmpiq.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gttbmzygdt.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtcuffzzpz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusbxrzcq.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtxpuakbhl.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gtxhcctzzy.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtaxlnkfdh.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtcdmllykf.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtdfejvflj.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtlpjaicfr.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtpfbwcflb.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtvjejhbmi.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtbdjestuf.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtdkcggzqw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gthlmmgvpc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtgnvfhdst.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtohlbsruq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gthlvncill.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtztacyaxl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gtshwpogqx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtmsjndlfz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtljpfggbr.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtbtnukram.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtzohapnxv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtmkugblfc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtnoaexofi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtnxvndeae.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtiillexrn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtpbyvkmlp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtyutavbsu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtcgdpigjb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtwwdofzqo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtofqyxfej.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gtnlqtunoy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtcopsucvi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtrxmdgkrz.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtogssqvxw.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtgttmexsy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtwzgtbaon.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtbxhbdsnn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gttytqegek.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtlrqzitpp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtfhgnqcdf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtumkerdos.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtpairbrzt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtsfrhiuhx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtrzprlacl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gthadxxhpx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtugncaxgh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmvftingr.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gtqssbfzyd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbnoutazv.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtdmzntumb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtrdwxryaf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtajldcubt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtakzhilej.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtuayydecv.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gtpobwixri.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtqqsuhepc.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtmcezghqz.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gtfvbxjjoj.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtzpwqaake.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gtbftajclf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtvrskhacd.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtymwsdrym.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtauzygkmw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtemqqstsr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtgbhfbfgq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtwruxtwnp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gticacfozt.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtzrwaqspq.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtphwtebvp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtadonrpds.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtppyrccpa.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gthkfhghyn.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtvegeavhz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gtthtotnue.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gtlzixdmeh.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtoomwttek.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtpcyledky.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtfskexvha.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gteyxlmmgi.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gthvotusfq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gthekzvepw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtwvtwteka.html


<!-- 参考信息 -->