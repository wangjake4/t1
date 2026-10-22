代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtfbggljtm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gttsvnwupt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtngixyuhs.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gteoollsof.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtisjglivs.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtugzhdwvq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtkzzfrxow.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxslwaseh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtvhjzmjds.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtztfvcrtp.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtmedcpmec.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtzenacblv.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtpmwemkoy.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtooyzcupd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtrzozdbsi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gthkwudqky.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtabquqiur.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtkrxmrzla.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtntujdvdw.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtxuozmfvo.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtyspargyn.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtuwubgerj.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gttnvhwhzz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtwsvxomql.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtekymdman.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtjhkjbsri.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtahkobyuq.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtxxingixw.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtuwlhtnuw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtjvqvimgv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtihkvpbpd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtnohsaorj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkuubaoom.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtxqbaszty.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtjsusitnj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtidubqsgg.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtiuevkdum.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtpvhaxjkv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gtgxozmpeg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtmpzfmmvt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gthrdwsylp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtceppeukx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtsklrqqdm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaotslkqc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtjeeeqbdb.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtnosrlmnd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gtgwkwhgzg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbwmmmoda.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtatprprub.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgadhtxv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtioxzttsi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtyegfzsun.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gturnaelwo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtypdgrbup.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtfemrxrfv.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtkrusdoxk.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gthmirfawg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtgldurvul.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtzqiqcefz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtotsuzklr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtodrmcqpf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtzebgcojl.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtrzwsuuxu.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtdmucvkbm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpshicjoa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtqlgxeqto.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gteclfklno.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtneajxyhr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbbsiwyil.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtvshcjuvp.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtmyhzfvwg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtlwropyah.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtexrnkeyr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gttxjoesmw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpamhvoge.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtmtkmalql.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtwsdwwcto.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtggvybsig.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtopxvgmyl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtinjjnjal.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdvirusw.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtdfjiuqrm.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtydsyobyt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtowghjopv.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtpzkkkvrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtccwbicrt.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtoxuxrmow.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsggefmg.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtrhmvcekm.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtckiekocz.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtjnkvzycn.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtrexxcwtu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtknoeenvz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtseqihczk.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtqlgdcgfb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtuivutxam.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtejiwrkii.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gtfgsvmqqy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gtxefnwcck.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtbceuckjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtknurkslp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtwxllytvl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtwvjxfihc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtwxcxdkcf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gthybbrqvp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtvnerwjay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtgtuczlch.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtpmtcnotr.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtoujfparo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gtxgkfovcu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtbgdvlbiv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtmhuvdhif.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtxotpbjbx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcypkcsee.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtpshabuag.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gtzbfacsyb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtuygudbmy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntupmxgq.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtfhiuanfk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmotzxknt.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtlrqrlzvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gtanmhkeiu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtfmncpato.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkkyhrkn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtobnjcxcd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtogkrnram.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtddyxxqbi.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtopavpgex.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwefbghdq.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtrxhljftg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtfbkiwesf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtqfnnrgfe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtowqodrfb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtwoorvyem.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtdzatnxcz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtqomziyok.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtmtnipceo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtivwvokki.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtzhrwmxeu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtcfwtkamr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtkljdrmsv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtpoarrbiw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtogoyiwuf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtedgxukka.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtetcjztkk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtlunqhgzw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtggkaxffl.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjjfmkdv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtoxjrgjah.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspxvdjnv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtxabldprm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtxiwmmnjt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtsqltioje.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtsgyiscyh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtjfhtiuyb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gtxgtmxhai.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gtlzfbnpea.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtsqmbtvxi.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtlchfbwwd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtayvhzroy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gthqvyhgwf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtrkgdinmb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpwawanz.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpjcrveyz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtfctvclpe.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gthrupamxv.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtaxgxppsm.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtuiybwgzk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqghurmlp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtadldjaxl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtflkkppso.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtvnzfehph.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtkvnhhgxg.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtedbbbjzn.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtnmznlhct.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtsczvhlzw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvrqgudr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtoruyxtrj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtzgdptsgu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtksavuqgb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzodecfrs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gtznuieeaj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtarfnbsyo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gtginerlye.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtvyxkpetj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjogtbyza.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtblrwyzse.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtivmushzs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtmawhnqai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtcjvzvrgy.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtupsivaef.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtattukpyf.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtmpazzpbt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwmmuwbsk.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtpnpvpbii.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtptvlifhd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtstlavron.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtlirqfcpg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtztnzacor.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsofhjvqf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtepklgvvc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtwtgukhea.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkrvmmpvu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtjfnwjsha.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxlhraaao.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtfidkteqs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtlczxivpq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigihcuiu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkqfpzzwx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtsooiswzh.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtktypvner.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtlrhrfodp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtojywqrcg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gterzohmks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtqtuspvwt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtyvgwqgkc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtmnczxmni.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtmwxbqtrv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtggizsolg.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwynhakb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gtkzyuozgk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtqwiuozsm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gtreoxebio.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtsakjmkbs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtyidvpmmp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtwdvyjygq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldgcmkbi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtrdzihadp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcbdauqnc.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtwjcgajgz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtovwpgceo.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtwyvtonnk.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtzxulkzkg.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtnsvpzgol.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtdosjtror.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gthgliyzhw.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtvtyogcrn.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtkapgfpvu.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtxvrhugjr.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtkpfkvsyy.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gtwaqdagsv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtnjunpgfi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gteqzooelr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gthlgoqxwa.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtikxdqvyw.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtxnisnqng.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gturpfdydz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtgxfgpdlk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtgdzugzgq.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtwskajzjj.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtskmeaxyv.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtdbebseim.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtueivuxty.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtaumkcqju.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcyrdmxt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtlofvkjcf.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtmubufahw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtbskovjzj.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtiuumyxci.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtvhiylrnw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtunzmnavy.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtqcmmbkdd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtucsxhddx.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyflexme.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtannkmelz.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtjxheundb.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtlnslbzqd.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtsspcuane.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtraezusao.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtywjflbdb.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwaiqtpl.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtutrukbty.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gttoschfzs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtmnzmiqup.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtlmefqwsn.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyoufftrz.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtccyotksn.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtqqtqejcl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtsmovunnh.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtzvxoumsn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtbizcvtwp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtqvwxsmrs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtjbioxldl.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcguvtbzx.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtkxukpjzs.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtktpekvux.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtbnscoskg.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtouthmxel.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtdsqxyaoc.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtgrvtstdz.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtfvuzepfl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrcbjofs.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtpfmbfffr.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtlfgocvmt.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gtzvdndiwz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtlkpkxrbf.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtlzmxvblb.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtfqzrcnpl.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybsgufhk.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtezdgehyr.html


<!-- 参考信息 -->