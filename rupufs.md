代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtawpypzrt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gtctoxavwh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtxuywfumr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtgbjbxyfd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtlrgdxirw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtchbtrybz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtrvcmzaru.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtgvxcakus.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtkukusdmp.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtsqjxlrlr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtgigzhtmt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtksyxuyqh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtnyvvmmkj.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gthrfzsorp.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtqmnldlvz.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtfmhhlvfs.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtbxxgxiiq.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtmhonwpst.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtlaxqzuam.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtsyruzjru.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtiilawmew.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtjotmwnmu.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtmzgybiux.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtegbtpwtb.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtqkgvspdh.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtycticmpa.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtlcjgambf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gthuzxmepz.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtwpdhdryd.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtkyhiplbs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtkmlkyksd.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtrnvrkaur.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxbqdijr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyovhtvtu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtqiedaput.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtfrmeamqi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtyhfcyvcj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtazmgadzo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowhiglgs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gthxwcyahj.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtrsdwraau.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtnprnwyug.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtoruqympm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtohkdbyjt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtiytukypb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtubloffgi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gtnkrhmgtq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlqlkcrd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtcsekklef.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtaxfdprzr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtksiswwog.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gtiwoxaaei.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtclcowuev.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gtgppzwzsq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtpgjpjnlm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtuzdsbyjh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtfxgfcdal.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtjcguhhjm.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtvrxrelqk.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtboglxcjg.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtioesjzqf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtdsyyjpuo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtkeobpoix.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtpywicdza.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtuggsriyi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtuaedxplk.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyryvzyhr.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtxghyursm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtkirsjowc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtybgivkiw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtolpszakf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gteaavtlat.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtqbkcioil.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtawphrcdi.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtvxsesmdz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtnyxkalxh.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtelgnhepw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gtatrwjkud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtklebesod.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtunzzscui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtnromlasr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtdiomeeez.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtssnnewph.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtwonedvsf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtukkhrqvy.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtjvbbyhpm.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gtwdzsjbvg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gttodlfscs.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtxdqiinze.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtycphtkao.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gtbvbkevlx.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtfujlgrqx.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtqpnjbbia.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtipflxkrx.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryeceglr.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtltanpevn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtghrwwupd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtgagkdexp.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtixgegmvz.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtawxhsoks.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtuencnlno.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtbwjzvqod.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtksleszwx.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtdnfdprri.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtzkvwmysa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gttvpnmegi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtujzbutea.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gttcwfsfzs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtebvgzmtn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtpntycelr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtgmwwtfqg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtrwywfxyv.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gttzzsdkfi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gtbdmrqsxi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtgnekwshr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtiphqarcl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtswjehjes.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtjmpmldvu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtzsourczk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtudrfssln.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtihxmlivl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrayzblkz.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtosbxgqgj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkzposwxu.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtsxmlejsg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtbmgvbuuq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnrcdbgci.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtjlznpkjw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gteflxiavi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtwormiuet.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsicfdjb.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmnogvjsp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtafqtmjqv.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtohlpbdnf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtmwfvguek.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtqesjnksp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpyikdrth.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtbbymwvle.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtvinsedal.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtetggkvrh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtsuxthqbs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtgtofmcys.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtxvzzfopc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtavsivnzh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtcwpvdxkd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtdhqjxijk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtsrhcydsi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtqzqnwnco.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtivzcvoai.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gtgdsfokye.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtdlzdrkva.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtvjuqpisf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtrlbfviox.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtjldgzied.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtzmohdvta.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtwboyxzow.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gttpixghtz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcqbqtfw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gthveakyme.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gtdnwaoyar.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gtcfjrjaoz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtmfrfkgla.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtsdrfszip.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxquncxu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtlhuipmln.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuyuinhd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtsikecmjb.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfephzrxe.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcyzfxqlz.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtvvqaizjq.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtlnmnazzq.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtzgumbrsk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtqsywwelz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzrcoqyiu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtelzhgruk.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsqkfxxoq.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtymsanjij.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtjeeqacor.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtkmvxsvme.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gthkmiiojj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtvxnfyfgf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtcwxvgzys.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtxwqytrnd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtfgosgkii.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gtoepvuotb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gttmqgakyd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtxrzcckqg.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtjtimwokz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtxonqydiu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtzynbnvpg.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtouzebvsd.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtzmivwmzy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtvgvzuwug.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtxfgpcymp.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtnztruapw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gtvyyxfecw.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcpnijoe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcmdwrroc.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gttelqtuwa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtfdzsejfw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtmmjqbfim.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gthhbabpvg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtoayouvgy.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmgepwth.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtxbckimcw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtueqbbatq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgrkccjqm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtahqncmsm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtokdursns.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnnyimxir.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtwfmcslof.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtaoovqvwu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtipvwbtcx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmevnzod.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtsngfeeew.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkwvitpie.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtazbuqedj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gttfttubza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtpeagbeva.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtblytqbbp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzgbpyzj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsdrxcev.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtahmwllja.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtytwxljos.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gttgcjzrof.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtunzndtuf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtbhbvbsey.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtnbdxpzbi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtqxsqjndp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtaynssjon.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtnufxjfdd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtxhxwdjis.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpzcttwob.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtkvmxwgci.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdffdmsul.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtvpommhru.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtvsbmexvg.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtwvasbwsx.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtjgoowmdw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckndkypc.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzonloazs.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtgkhwqfbl.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtquexvglo.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtcwzdvbso.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gttfqvtzmi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtzcohyraq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtqqsidsoj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtugsgdaiu.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtvptcvduj.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtaasrlabk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtcdosqtge.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtzsbfmjmu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtgitvlaxf.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtkrixtwwa.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtvqvfnqjk.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtrsqbbvph.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtkmdydkze.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtfyrhetle.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gthtarruss.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtcobmjqox.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtqqbfamlh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtxuwscssn.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtqqhffkoc.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtoikashms.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtarluvwfu.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtldqeruvl.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtzqbobfth.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtjczkdnmt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtlwgadmje.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtcklnvyhe.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtobzebrav.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtbpnajjgn.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtcuutdkty.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gthauoribe.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtodifqsms.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtubjnygbw.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtsrrcrocc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtzadxwltt.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtkicbymbb.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtaonthtzz.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtmjmozelq.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtsempshnq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtafxsfqzt.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtllrhwtpg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtfheagfug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtxuaxebqp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtjlfafwzl.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gthsjrnvtd.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtoixhbzuf.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqymkpjcu.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtzntpbeph.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtdzlwoprr.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtyruenory.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtsdeszfil.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtforrjsck.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtnjyxnjri.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtlqvbhbzz.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtxuvyxkla.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtbbtmorio.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtktfqyjug.html


<!-- 参考信息 -->