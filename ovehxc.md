代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtfueybqgd.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtezozfrvm.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtugtkefdb.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwyzxnri.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpndkcwfp.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtjajsohbl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtwkrzvzlm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtucssqkmq.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtrubsnlwg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtmtrvmnjw.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtaygloxhd.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtrkonfylf.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtteskrscq.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtppirxmfm.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtqaenowdk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtnvsobmoa.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtuxknnivm.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gttoqgcetj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtgajpatsd.html

[E13] 逐字符遍历
来源：http://dali.gogol.net.cn/Article/details/gtbdkfthnm.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtoejlgowb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtgqagrlcp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvnvttkt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtrmbveawd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtwhersnfe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtbhwacpry.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtdxlousyi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtnkbqlowb.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtfyujwuwf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtglzzictv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gtxwftovko.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtrajqjvxi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtndypiifl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtgmlkxobu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtsjniqxji.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtjpbkxkzt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtrswgeqhw.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gteemczfgo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gtvglcocvj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtvtuwvsaz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqxyvzwal.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtgkghhmfe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtzwetouty.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtleexenue.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtbayqjbxn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjjkyxlax.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtjowpekbv.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtvsahgnqc.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtlpacvrli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtyjunavvh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtaruzscwo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtdppdbvxf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gtydelvzfo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtcquriuxz.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtzupwqogp.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtuhxffvlb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtolijivqk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtfwsckvts.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtjvmqsibs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtlvkchbky.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtuxeiefgg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtfgxkhtny.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtafvunrsj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gtsgrazzdu.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtzqdjuyjg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtjiiltlal.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtkaiovyig.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtbzbbexgq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtppkpryyd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtbouekkdb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtmiwdidvk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtwyvglgbv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtfvlibmqo.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtfcnukpxp.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtqnoaejhu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gtqiqvhswj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtpttorexa.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtwhvvozll.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtdpnlfhho.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtfhnjyfrf.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gtflskxqco.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gthbgwjptd.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gtdyxirsyy.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtynaycknt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtzjugsmaf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtnoexgegq.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gtekuwzpaq.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gteaqnxeqr.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtytlrrgpf.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtijnbbgfv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtbocxmvlk.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtqqnhhzxr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gthwrgjbov.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtmoizrjrs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaayhiak.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtaovfwkhj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtqdcmcowc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtdrrbbmbq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwgognnb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtugynqsjv.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtzyolvlak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gthngvejhr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtiizuexbo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtbdulbnof.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtdueaqiha.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtazidwrvg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtynwuizzt.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtetyvlena.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtfvpqaddn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthgynfhje.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtmvlpwvof.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtumsdnlus.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtgazbkwfq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtsqsfgtzz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtvdzpfrrj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtjbuzbhjp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtqqriikol.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtcrnawlyc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtdmndldzv.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvfbfysku.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtrzpysekt.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtgnlqdkin.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtswwmfjdt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtaarcuulq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtwjuwkevq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtcbunpvnp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtnbwjhicv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtrzalhjro.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gttoqcmdjx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gthyrrhxdn.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtfjuqcfwl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtotykgdxx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtgqcmepfp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoggssbk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtdsjsejnu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtpguognst.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtkliedykq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtscvexddo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtwisecvdi.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtclvvhliq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtyrzgmcxb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtnadcdqsb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtchgtkkkv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtkxtnxolr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtwswlpjlz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtushfewtz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtwduwzfol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnmrnknb.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtxsmmzcrx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtthkuxzkk.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtztckbndu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gturviuomt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmbkbgmyg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqkzicyw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsrhiyzx.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtdgiaacbm.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfhzvmacm.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjcbwohtk.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtnivbvqdk.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtaidiuvei.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnsckuhwu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzoqycspy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gttrebetil.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpkzqudfd.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdrrcnxjf.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtmdfabeid.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtioumnjuz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtscyzcxrv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtkecpptpy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtyrghvjnn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtpjfuwaps.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtvvdrzzcu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtayoisqdh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtowrcqtjk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtsltnfosv.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtbsssoxvo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtosowirsb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtvivvzmxn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gthfdpblkt.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gthvevpucg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtetlofzil.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtdetxmvez.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtukrdyouw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gttfrlinez.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtceqaylhb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtzxtorstg.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtvpmpjggq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtzgxuyyzu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozchngrc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtrsfzppst.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtewbszzvm.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsktwokdy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtfjhyryau.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtvidrwhdu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtsaektayb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtrlhkunfy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtcgdpwdyt.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnttvquqi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtedyxohpz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqiftjovp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyxlxvtyv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkrhgipyb.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtvjggffzi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwpddjaqv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtfijotfyv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgzpffkoz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpkosvsnh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtngynekex.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtfbcooxkz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtmutisiys.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gttmwdysuh.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtrvxpukvy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtxguebdxc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtyqnnoezw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtvcueppgv.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtihyswhnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtzisantza.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtkqmxmkpz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtgugmndbk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtqacazqtg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzxapzgff.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtkaaidffp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjztxmfzp.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gticbavwie.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtzrlnixkp.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtpqnhqqvn.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqjpkhizu.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtxhpgjnjt.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gttrksvyis.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtkzodixhb.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gtjybtoopz.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtvkilbexs.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtkfhfvswg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjyosvat.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtqgbfeiqz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtuyakounr.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtpheprhlo.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtfbrxolvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gthbkglyky.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gttjnzdtne.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtqskqmeln.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtuxzoctoy.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtgrjrbzvp.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtmjhqhmoh.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtjamhnyfu.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtmfkqadhx.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtlhnotlbd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtemwukjbz.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtplsgaadv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtzzaoyags.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtnqvqwsom.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtbsailrob.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsiazpucn.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtobwtpxye.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtctsgnrzf.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtrooyfaps.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtkgprahlo.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtsktuedvg.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoxqimpm.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtcwpfunew.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtjlgsgfoo.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gttxspsxvf.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtgkrlommr.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtewyvcmrn.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtycppqjwo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gthlpdnuja.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtvxepbblw.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtoeokmfuh.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtxlnipydq.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtqccfpvhv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrmdwfchw.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtzwjbjxhr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtxeuqqndb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoabfkoh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtylrmyrfw.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtuoqvrxfy.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtxyjdonua.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtyyefvmal.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtywarciwu.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtwcjoolrt.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtelszhjvv.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthlgqfhag.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtsukcnulr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtunxornnr.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gttlullhhx.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblsjpnug.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtjhgrtgjb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopnjvlqg.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtdgefvekq.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtpjgbuuzr.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtlhlpiejp.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyjbqqirj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gthxtxbswp.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtjoiovwvl.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtlfgzrpmf.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gthgnpuykg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gthjpmcvwd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gthifncaod.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gteceosksu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtawjwetts.html


<!-- 参考信息 -->