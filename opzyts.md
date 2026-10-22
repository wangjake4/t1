代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtprzzzpzm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtifgdbbbd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtyvfyjzxf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtruzispnp.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtpbjmusif.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtuaskdini.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gtcyufihlw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtmiokozui.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtxyijzzeh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtpujxbbat.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfztekuzv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtlecridda.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtddzawvzv.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtkfwuppin.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtiikuzfvw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gtwzbkhakk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtisaulwlf.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gtobwzkoml.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtvlegdrqo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsuyjelka.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtgoqaqnvs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpmenfsc.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtxhudluft.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gthbomaxor.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtcstzrzvr.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblaikmhi.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtlmnhduum.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gthpnfgrrr.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtbpowgttu.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtyjvtytus.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtoqfsetxn.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtgyrcmfkr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gtkzyfzlko.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gthbaaiccz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtqskytddo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtflgezsql.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtglmwfdbv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtrzmfagci.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtgrgrzcwi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtrvvqqvbn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtobnepedg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtyzucuids.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtempntndu.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtijqhuzsc.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtqythfkqx.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtllaypglq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimwdclfg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gthdpxhnpw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtzvizuvsf.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtvdrphnhm.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtrufhmlgk.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtbcoldfwf.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtswpwkowv.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtavofezvc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gtpgknjbaw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtoktgnfph.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtqvlmtbgv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtwudwrdhe.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gtvypzqdrj.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtfpbdyhem.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyczpdyl.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtaxqedytb.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtbunbcfos.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtewwyyayy.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gtcdvohoyw.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtempzoyvj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtfnmgmcmu.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtcwufzlle.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtnseejosk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtyvjrswfd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtljfrlnkb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtdfpllnue.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqncnvuvc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtukukghus.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtqhpektcu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtlydbsoqg.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrubrrzbt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtjkxbbwdc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gtzqyxydpy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtolcgzhjo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtqoolouno.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtkkldozqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtkpcaktvr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gthegaxfxw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gtpkrpfonp.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtpygsmhpg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfcuglrw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtzivaibxx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtwqtbaikf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtlzjjoutb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtdibjijjd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtxbmiemvh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtuimewrpk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtsuflvxzx.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtcvpydsyq.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwtkkwzs.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtcsckfpjd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtxckdtofa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtkhjhowhh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtxngsyhgy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtjpcqoizp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtgetsegfy.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtsstvqzke.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtvhqwzuht.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gtbepxolds.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtdoktdaki.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gthtaynrtw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfvrhecwk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtkgxvbwgo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtougmwkgr.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtmcmtkldw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtekdhylts.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtlwfjlwuu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtoptcapsn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtntuyiwao.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtajzurtlj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtfemlyunw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtyzrresco.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtmgcqvfdr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtlqcyzpza.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtgfossocz.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gtgdehfrvs.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtkvbfgdiz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtyxvtasds.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtmrpwbrar.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtlytzbkcu.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtvvkiigzz.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtfzcgkqdl.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtimicrmus.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtctstwxyy.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtdzofczvq.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtqgdniqgv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtrafpdrdb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtzddolgmr.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtsuhczcml.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjropqlqw.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtbpglphuo.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gtemidzsku.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gttmjuuwlp.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtrhibtdnl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtwoidcocv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtwmoolfnb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gttyadsgkf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gteocrottz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmriabgc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtnysxjicu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtpldpbiae.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtgvjpuuuh.html

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gtrprfjaoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtierzrdxw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtkpzgrded.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtxgcaouvz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtlabncspo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtjiuuzfti.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtniojfbuq.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtnpxvtcqq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtuqenkfox.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkkmpenrc.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gttytalmtx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqmicqiep.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbozijvjw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtbmkjutgp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtmzfmyyea.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtlhtzzvfd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtwadgmxbp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtrcokspaf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtnjfyhrua.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwnrdxvbz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtsscxifvd.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdrmclxzv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtfdccfdwy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gttvlrflmb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtyvmyeuks.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfubqcrc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtppmxgxdh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtuykcpofi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtzjyaxsnw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtvoqnnihz.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtavuefiij.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtaqfwyxeb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtqozknmeu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtcqskcfjy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtqsitqqtd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtslfbauyk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtnlqwbpct.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtwollpucn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtnkdgcgin.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtvtlqdzsj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtkozycqbc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtzikescon.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gthmibockj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgcrcmbb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtkmdakjiv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtfunbyrxt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtffzyqvxj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtwbfimgif.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgunyiiye.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmvygmnn.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gttctwowbu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtgeusexlm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtywgoipbg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtxqciscly.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtlvkxwzik.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdtdbqari.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdnguqadn.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtowgcfpym.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtirxxxtwz.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtigqafnvr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtazmbvpnt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gttauestvi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtmqzqioph.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttwqpnsol.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsvahuiic.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtpltpzacj.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtopkyuxsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gthygcvkwl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gthntxxjph.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtnjtphlkx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtfzmufpqw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtamkddihh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtbnlkdtwa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtwwjivpcu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtxaymqgrh.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtfgjddkhi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtlzqiesfr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtufkctddg.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtboqkjscm.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtgdmimtkj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtlqarmrpf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtxuksotdy.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtgsdzztcz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtbhemfmsf.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtdutbenjl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtnjewnisi.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtibzvaurj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtuwivylnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtpitpunnx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtwfzhzdjg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gteygvsxrs.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttbseelfa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtthihqarp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtszsxvbhj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtlduhkcnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtqsnmgevb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlimcpoy.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfvwjqehb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtraveyxsq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmecpupng.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtreqahebt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtaheylvhc.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtksydifro.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtaqmtltyb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtvwohdiky.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gthptudxss.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtzmjaqhzs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdejglamh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtoaovspeu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtsumuvihr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gttgeydzxa.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtcblygnoc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtmwdsmzfx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtuygnqjmt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtebalfuig.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtckvhmfaw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtkdiqkxcb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtkmionufd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhrvpjta.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtyyljxigc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtodjcihnw.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtizcuzktl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbsgtzaya.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtfgzxpgvu.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtsiodyznp.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtglduwpxr.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtpcywoche.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfudfoqjr.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gthaviquyq.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtwuzhcdby.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtfcydlbga.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtjztpkzle.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznrhoarh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gthhkhxcjr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtfdafyiyb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnnymbqpe.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtzxmemjdj.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtdfanytoe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gteibfdkij.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtsgrfeedj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtvnmgeguh.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtbhtjzifb.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtxwfdzuqx.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtwgeaskpz.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtgnkhyplo.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtcpcoxdys.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtgjaipayg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvgzlwue.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtbmtjnsym.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtlundxdul.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtfnnoicqu.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtbwplzmvp.html


<!-- 参考信息 -->