代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2pfwkzrhw.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wovsdcib.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2srutafmd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2vrpodmwa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmuvzjsw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2wxgnvznt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2utpfxdun.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gt2wwuzyrxl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2jonvynbv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gt2zvucifby.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gt2qsiyhdhc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2ddnbckvl.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2ngmwpkjf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2aojnjzey.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gt2bdgwwyik.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2fideftlk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2fgxektrf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rztkcgcb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2zycvbxsl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2pdnvnkqt.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdjkzscf.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gt2fgnbixsg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2icpsxxwn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2smsiixkm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2dyisrhec.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gt2dahdscgk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gt2bmdhgcwb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gt2uwrexadn.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gt2dzmyrdss.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2llgeojjk.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2ohvrmqvr.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skhuutbp.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gt2kbhahqfq.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihpqcade.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2ghyvmjqp.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2ulecmpmu.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gt2rsseanmb.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2gxxggzpb.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gt2zulirvnz.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqtmvsuj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2oduvdvyd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2efsjixge.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2vqbiacto.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gt2zysgidic.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmnwsgua.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2wpqzbvhf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2jtiqxbks.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqkzxsab.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gt2pzsdrgil.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2yzotbvge.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gt2kpjpuifn.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2tuazeryq.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2bnlmhhxy.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2orbchmms.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2hpjbnbvp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2loqgtktr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykfmhowf.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2ywzginfi.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2drxibxjt.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2phsxivyb.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2cuvejwhr.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2utpiopnw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2vmxmhwpb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2ztgtsitd.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtxzzqdv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2hqenbbdz.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2vjxxiqvk.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2edilxeee.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gt2ipgoteov.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2aytfhnbm.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2vpdjtfat.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mumwifso.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gt2qoejiuqb.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2joxupeqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2wdxdentq.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gt2hjxviuso.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2ykuowlye.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gt2xmpqyous.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2pfznbjpm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2fqzkgzmb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2hbzfbtvl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2ulmjagzt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gt2itzbukkj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gt2lohfhpkt.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gt2snfnifuu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gt2fiahqhct.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2mdeywhto.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gt2njidxhdh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2scenrmda.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2idopfzzk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gt2xtcwjkwg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2ysgksrmc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2fmggcenr.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gt2ykykfvvy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gt2tzqophce.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gt2gcgpylkg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gt2hvxlkzzl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gt2jaqjdlaw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gt2jdqlklap.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2fhugsnjn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gt2ivduzdsl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2alukozfn.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2gitqphzd.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gt2rwspvbws.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gt2qpfawtkx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2wdsirkfr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dglbvprw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gggxmmvm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2ykjmwslb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2imyxosrl.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gt2bpykxutq.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gt2kqlsazrx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpqdfflu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gt2jzchqvxu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjyxzazq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2favveqcb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfuimypm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2muikxywp.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2jyrsdcaz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gt2wntrqsra.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gt2ywuaygkx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gt2rgrynyzk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2thakigvw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2oyqbijll.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2ixkczgwa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvmtbwmd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2rpkyzrej.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2xgbwhrqt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gt2fhxgubmf.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gt2nprvdiei.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2tfwkzzrl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2yvfkxuts.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2loplrmfu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewhzvzzo.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjklrboy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gt2xynwpnwn.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gt2hrozzfcw.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gt2wiaanino.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gt2mpslrate.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2shclbddq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gt2bshemkwo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rtygyjpg.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2maeuszoh.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vvddfrkz.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gt2zhphlqnb.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gt2yuatlohb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2wwbzxwqg.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gt2jphpecog.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gt2tqvegnwj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2ewxxweel.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2sfluktok.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2mjpyjzng.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2ycytclxq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2lcyrliqv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2qhxlqnil.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2axdotykm.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2fnuyqtzh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2dodijmcv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2teikxrhh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2oxpzserv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2cexzbijs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2zntqpmef.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gt2wkznduic.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2zygwpgwc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2jfpyvpyx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pywadvsb.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gt2suznyszx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dlmepjbo.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2jzzwyixz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gt2tmvukucl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2duqwfagq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2veglyeba.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2zczbgjws.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2veiytrje.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2ondpqobp.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtvbstcq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2tkctopnn.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdyulimi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2czyhgplh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gt2lxjeiovw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2gwzjxyby.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2smmckryh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2wkoipxru.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2gqraftks.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2liwbuvie.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gt2oklktqkk.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gt2imlummvi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2rjscixqg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2fibvjllt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2vpgcygev.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2alfhbbax.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2mlpfluoi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gt2alqonhpk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2updenleg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2tjyvuplf.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gt2xunslpbp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2tvtewjur.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gt2bamomlfc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2qopfgeja.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2atwbyaih.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gt2eyiwnbko.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2xqhspfth.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gt2smcvlmdz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gt2mknplozq.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2uxzgaorw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2jfrhwcix.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2zemgqrsr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grewsgkt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2zhkjrpvh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2mridgprv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpyydyhi.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2nrfcvqse.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2mfvwfkhc.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gt2tykebjjr.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2wifopcfa.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqyscgpw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2kygaaogj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2qvdaztwg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2ecevknmy.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2hgqubqsr.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2hjfgimwy.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2vnhtujog.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gt2axsjceim.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcsacvag.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gt2pbtomtnm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2faaiiorr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2nsnvmfvt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gt2unxlkzus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pztzfwsv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2kncgdpka.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gt2lelzzruv.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gt2cgdppdym.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gt2zhqqmnir.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vqvwmwyc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2cfredpqx.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2ukfcxsjw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2zelteysw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2oxiyntif.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2cqvvpobl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2gdmovxnl.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gt2ltsdfhrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2qmtqyuhh.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2yqfzmjnb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2lulgkxiq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2mwezvtom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2boakxwst.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2pgkpcuvn.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2vqvlojux.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2dsssfsje.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gt2bzkkdhyn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2fcahizsv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2sovylaru.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2tisybbbg.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2mbqvpuzt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuodrnsv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2sxezajgj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2gnyjqydw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2pnlqylnm.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdonzdzp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2iftzeadm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffjwmymb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2wisbvvee.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2sesxjuzm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2uzixvusw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gt2jjpyvjsu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2esaqkpil.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gt2ojweedlp.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gt2popzfaey.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gt2josdcmax.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2cwofheka.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gt2eutbezis.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2dyfljxyd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2vzdghksq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gt2aikvaacj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gt2bznoodai.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2stqzciyk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jdpsflnx.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gt2fajyxuqt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jifkgleh.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gt2jnzhhqzu.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2fchqzrun.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gt2gnvbjafg.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2nyrfecna.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2hixdgxdh.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2pknfwjrk.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gt2mfnepcgc.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gt2ifyykfrq.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2qsieuidi.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2yponnpcv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqrdpkgr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gt2gkvlmyjj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2vhfqchnh.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gt2omjspxyp.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2lxncozng.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxzklqeh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exkagrva.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2eyvkblvp.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2enbaxtho.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2zqcxzkln.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2tojysowf.html


<!-- 参考信息 -->