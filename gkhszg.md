代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtgnzleeaq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtjpeynmii.html

[E08] 数组按分隔符合并
来源：http://dali.chenzaomai.com/Article/details/gtzsacfawd.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtibralrpa.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtcdeovgqo.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtsqnpghnt.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtxmvuru.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtzchlilzy.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gtcmahzhgs.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbrrzijd.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtomtpgnpk.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtzungjwjr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtpewpaqqa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gthuykeagk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtlsffnoyw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtnlpelsxb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtofuwzhtv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtmgfzfbrr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtqolbjbgp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtfjbddorg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtbozjknwc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gtxusmoglq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtasccnaek.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gttdxrzkcl.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gthqzhbloq.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtgdhqllzb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtsjwnpfzf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gttojvrujz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtghymxaez.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtzvpdpnuu.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtscyohlqf.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtllwuufip.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnupqfhrd.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtbfytaszj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtusguyxid.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gttosbqwuk.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtcbfdmkqg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtberelsuz.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtslcvzmfc.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuimlrfsd.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtjbdtsmmt.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtoebwchbl.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtftlmqmaz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtuknkrfsl.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtwhwrdzkr.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtqydymxky.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gtmjsdfuge.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtacozkbjp.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtiwouudoe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gtbwzpsiph.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtbkebzsjq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtbqixgfnu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuwtvoht.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gtndbklwxg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtyrwyajpr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtodvtgvlv.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtmfhipycm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtjymtirrj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gttqlzvpez.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtbtvfpzhw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnoigchdb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtluyqkxlr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesjbjaxq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtqbtukrsr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtpsrtbyvs.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gttidqaaiv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtrmqugltc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtdnzhuyzn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtqisnbzox.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtadrpxkvk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtreukocyi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gtejhrqthr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtqkdddmpi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtaocnpews.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gttjwclmlu.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtjsjhddxq.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gteddevqpa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtbfktianu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtlbupvjus.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtxvxyhaym.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gtsknxujkf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtknlmozwy.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gthwmgvlub.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtretbblsl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtmyszsgrl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtxmfdmpyc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtnbomqofp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtctlqrlqu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtqrozaugi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtkdwzhvml.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtriumiduq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtmkyighpo.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtomipkubf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtelnbybmf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtxbqfjfdv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gteudhhmog.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtedpdsaxb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtsqvopktd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtnvglalln.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtslgdrfdt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtvuicajhj.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gtduxwzcju.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbhotdzp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gthihcxeri.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtgyhomszc.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtsaxkybzy.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtmpvsuvzm.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtypkjqueu.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gtcgntsrul.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtqvsgmuuk.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtwzmaizqm.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtrzscmfbm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtgcshacky.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gteltdgjrd.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjutvgahh.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtpaiwbebd.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtmuhrgkld.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtzqspampg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtuvmzvsns.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtcgnxehqx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtnmeouxzw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtwenklsbp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gthepdbeds.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtweadbyth.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtjuzajvlh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtkixhiuux.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtvalvrquu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtawlxfgrk.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtbfxgmqfu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihhwczbn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gttoecrhbv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtnsujnivq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtcerkswgp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtcwenamhu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtjnevtbef.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtjkauvamq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtlbnxcpkd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiyxuyxcf.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtudfpunbj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlqllfkbw.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtnczaysdx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtdbxkylod.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtcctbdphe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gtkxvjjkje.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtirukuslg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnrivipeb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtpdymlggb.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxeclfdwc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtcwjmlrha.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtnhkpjdvh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtxjymvjbe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtritkubix.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtofbbddkw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtsdzqrqqn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtfoyhcskf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtgkajiigo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtxrdrqzgj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtaxcoladb.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtmjqauvxg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtuyndcmgr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtbufxlehc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtwxwvmkru.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gttafjiwgy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtnpkchkxc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtabfpuyde.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojltbsks.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gthgqylico.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gtdzyxmrzx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtlygysqql.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtngkchtzs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gterkdjuln.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvwylhrt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmvyuaww.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtkvyugdhl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtdzkbgqzh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtjbrzpcow.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtonalwyql.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkeufyyl.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gttgdkunhr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtojbageuq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyjhwfltx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtdrdiuucx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gthqtlyzxr.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gttuujlwvb.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqhlkmwhb.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtdwlsqlle.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gthmhjjtur.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkkzlxvad.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtttcopith.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqunhboeh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeaorukw.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewpijkaw.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtggvktocy.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtxmlvfdco.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtenxqsrqy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtcbogzorq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtuldwladf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeqkpwuk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtdnmurahg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtwpycljri.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskvwwxpy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtoynbjfhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtrmvchgvi.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gtlzfxlgbk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtpthpunua.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtcdoumkzu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gthubzijqb.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtambjaheg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsyzthrn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gttrwuzloi.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtzqngayuu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtcmyfwyuf.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtyhdvwrxf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtpsmfketd.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtkiftipmy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gteosbyjhl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gttysdvika.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtypiwdoub.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtfupppyvi.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjxkysyps.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtjxjfsbii.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtutonzxpv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtafxtjzby.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gthjfkjolv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gttayvhcxw.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzpqolmfc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmejrzclt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrgeqeomb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtowxizwvi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthcsjxjg.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtqxwmqouw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtdpidaukp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdyqldwj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtwkvyfpvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtbeudiecv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtjlrivwgg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtjvaxhbkq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpsscqrbh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtnxmlbkcp.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtvzevicbk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtrmbezpwa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtltpcdqsj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtelconagu.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gthziveptc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtpoivymmr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtrltnggwq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtbupkyvjr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtswovvprh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthmswlajh.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtdivvkdcz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlpoihzlm.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtkskpnqky.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtevxytmgp.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtskcwrxed.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtsrrdkkno.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtdnilhedo.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlwiuaif.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtvcowkcvn.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeavvuoc.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtpqyzbcab.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtfrxwzmzn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzkmdxas.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gthtgtzedd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbohmjnss.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtcctzwzwg.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtaixxndno.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyzhfeul.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtkpvtxxra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtugameavc.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtlmwusavy.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwixuvzdj.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtqrflntzy.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtrevtodus.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtvbjyvkwc.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtkfqjincb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtvsvxless.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gttqemtnjp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtydvybwlx.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtcxzgmlih.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtcewcqqtx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtqxikvmuo.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtekjnxtzj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtnytmeqpj.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoudhkrtw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtbmghrcng.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtbgakzscw.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtuqukdcrh.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtpznivkwz.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtyheiawox.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtfdijctdj.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtpamcnobd.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtukzuyorw.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpkarfcj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtrkimcjpv.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtdwzxkytm.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtyrfdycyc.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gtxbknanhe.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtohvoivds.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtoltlhtvc.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtfkpmcukc.html


<!-- 参考信息 -->