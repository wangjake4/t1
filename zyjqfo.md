代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gt2vbqgddbz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iacjtfvg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gt2qmawwgvj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2xcliispi.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2sdwfupcv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gt2hwlarlac.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gt2xjhgwjeq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gt2gaiesbpu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gt2cjziigoo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2yfjbzqra.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gt2tsdgbpsx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2jxzvqiys.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2gqujupxn.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2dwxajotl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gt2ybqdvvdc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2falcsbpo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gt2rwchfymw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuugswtv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gt2rnkndkhz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2rxtfgfgn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gt2fgeizata.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2lvqhctaq.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2ofhzjwbm.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gt2lfwwuxgq.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2qwtmmgmq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2vehlxuvd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcmapueh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gt2owkfddpp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gt2mshulcjn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2jbppeelj.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gt2vvbcfirb.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwoxqtqj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gt2zfusqtxj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yugywohv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2izxgyuqt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2udlqxqle.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2gcmhijxp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2tesecssg.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gt2ornjzhnw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gt2jjudetqd.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gt2hgijoljm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gt2tjtfbghe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okhlnyyq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2mcxoqoeb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2gqvihhuq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2orkpcwrm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2gumbjhsw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gt2lnsswalq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gt2knapubub.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gt2pbnfeyvf.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gt2gvbaazry.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2mjxedwwj.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2vswgpwdy.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egkyrqvk.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2kxrodetq.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gt2fyiuetdz.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgpzulqz.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gt2ffvxyvac.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yekfrbbb.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gt2tyaxrkmz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gt2uhjyzpac.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gt2hycdrkmn.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gt2pufhyahl.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2smjyalbe.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gt2axwuxaae.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gt2tmtzkovl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gt2hdfbsbmj.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gt2tbyxefsq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gt2funlrmji.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2bibbckyr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npmugujw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2gflbdtru.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2ehbratkg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2cyrnwceb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttyxmxlq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2nsoihjfq.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2qbzjgril.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2nidptzvq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2mdyhejsa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2woftbpdj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2ufmswlxp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2hripyghn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gt2knxjacxw.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2slwglizc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2lsvzonyc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vrbujfgx.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gt2mtwrjmav.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2eblexlgo.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gt2kfkvpere.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2bzhaophs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2wielwcxa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gt2mooagkrb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2ruibizui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2lozykuei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gt2mfiuhhqp.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2cwphknna.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulgfqsdv.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2exajstmh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gt2sfsxbjjk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2dcawsqcf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2tzcvbqtk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2orsxywtz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2qrszrbyg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2kbgvjigv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcsxypmi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gt2pmklnmqs.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2trkjqbjo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gt2abokgfjg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2gkxkmapz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2fgzdusjd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2ljnyvyot.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2pcbvziog.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gt2ijxhwfff.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2elmoghgc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2dfmhhvuu.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gt2vyaemlej.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gt2zuzjotdv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gt2dmgndmmo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2acfpvhrx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2vwfuorxh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2gouezove.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gt2iurtsqxe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gt2kxhmzmym.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gt2mrwkhelx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2xeqrttcr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gt2ntjzptaf.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzenzben.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2vkiauczx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2qmmazggc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2imcecwme.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2ixvwsmte.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2znzbllqj.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2jfhgpcjb.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gt2wnsxqcvi.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2xugacpvm.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2zkvliwdd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2hkfdkgqa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2senbfcbp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2frwscoyj.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2sgxltjcs.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2jkusexsg.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ufaxzfxh.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gt2vlzhimdx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmvebkle.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gt2ywhtcvps.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2uthjcpqp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2rsxkzoki.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2ymysqndx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2qqeyuzsm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gt2wvxcdqfx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gt2azwjfnbi.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gt2imauqgbt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gt2lcpcmris.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2kakbxmgx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfvllsz.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2spmeyrfk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfvtonth.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2yelqyrki.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gt2khedumsa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2flrgwxot.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2sydbuybc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2fndqevkb.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2ojlnklli.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2vimfirxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2kvdlwvwu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2pxbcdnmc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrourtfu.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulfccjzh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jugbpwqs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2urlokfme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ckbmlzot.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2wqyzsher.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2dajblkor.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2epkdnvxw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2crfeauix.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndtulcrh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2alymttzd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ozpoibdt.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2rherckmf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2ccilogrq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2qcbpmnvw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ungodnep.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2zxajqrtd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gt2flseidfi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2zpqyzfta.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2tnystktq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gt2xivgmuml.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2ptkbqwvj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2yrtvdtdl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2pdxjijuz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2vimrnktb.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2npxcgpui.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gt2xynkjvxc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gt2peyzcchm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eokqkzoc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2joptkine.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxbbuuix.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2fgthewtw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyffhjnz.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gt2igxzgkbl.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gt2hhyqlfkg.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2qyvfygky.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2oarejwhf.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2szjsecro.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2lbuneatu.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtgfntgf.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gt2vpgotyng.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2rputwcnd.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gt2ovzqqbrq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2eszrxvmt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2xxfbzyqa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2zfvbiefo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gt2praqrowz.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2orduapcv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2ophaikcz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2ypmknhob.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2ymgxlgiv.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gt2cjxzswrz.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2gfceddga.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gt2eiihlese.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2npyfwwen.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwwtjchl.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2jntqfauj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gt2qfmkpvby.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2aesboxdo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2abxcrsxe.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2kqkylhkw.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2qjjegkzt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2dkemsiab.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftxsgkbq.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2vgpztwcv.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2wqtqntnk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2qjumabaj.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2sirnebiq.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2bbjzbcqf.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2aiiwhqgr.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gt2gajuctui.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2mltqfhhj.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjragwht.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2gxcuvoqh.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2oipasigb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gt2siwslbhy.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxvbwteg.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2hmdafrzf.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2swoyieei.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gt2uslsftta.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymdyajnm.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2slniguqz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2eonmkyeq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2rgasoqnx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2gwruqwpy.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2wpswinbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2sijenuay.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2ugkpbssx.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2iifqriaw.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2bcizljdv.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwxkuaiu.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2okltgdcl.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2mfdmvynw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gt2hfzeqege.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2snrydwyg.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2daftbwkd.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2qsoyxijd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gt2lajwukwf.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gt2ukvpxrtl.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gt2pjesabpq.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2viaewdxh.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2fodsfrme.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gt2wndhsomy.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2txjdfhwn.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgumqybt.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gt2cgwusqns.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2tpalqzrj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gt2qbrxqovc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gt2wppzhsvj.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2iyjjkbwd.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2yejwdkrd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2ygftyycf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2ckriecut.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2ybxbsivc.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2pdtkspjo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gt2nyzllwxm.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zklvskfp.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2gsqsaxyi.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2muhhbjxj.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gt2kfjxqzwp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2mrxpjsnn.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2qssuxhqg.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2skhqaaip.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2ixublmcq.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gt2hznmybfg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2uedohhdq.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2zbbxagkc.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2tulggoxl.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjdgpnte.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2vrwcajvt.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2zkbnbgbp.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2thmaedjw.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2pucgvbwm.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2vinmdpao.html


<!-- 参考信息 -->