代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcntcnsnl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gttacohukl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtmpccytmj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtglyqcvas.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gtkkalcqal.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtodwpmesz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtqaxbbjhi.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtiuqvnpog.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtqbpxjvct.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtbutewsdg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtgioseyfr.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjnngsrp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtatytbkna.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtljdtdzix.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtkbbwuecu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtxiwvusec.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gttcezdvew.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtjhpainxr.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtvqvfhclj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtpsyalxjm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtbfwxyvbq.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtpmdydmqi.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtazaheowa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtxlhkbufd.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtsgrrlapz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gtgkfgeapg.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtvddakqls.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtgsgrsbwm.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtlufskfdc.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtwtioyuvs.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtldhtcmie.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtdcefvxoi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtuveeaspw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtixtxewuy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtukzycgwo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtxxkyliwo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtiwngoawn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtywrtbgrh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtdqgubfmu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtvhwiigxg.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtphhfyhvz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtezzniall.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gtrckygvff.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtcyzvuicm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtvfutjxhj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtepabeqqk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtttlprnnj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtteeevlod.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtqinpgrza.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtvpofbyhs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtlxsljcof.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtyvzkylfh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gtgcbrbick.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtsfhrrxlm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtphouzcwd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfyiinpmz.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtmcytrzwk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtazyewglv.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtvgxvgshe.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtlajoeizn.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtnkdohuna.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtiuxpfhpe.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gttkpliizm.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtvcjzwcde.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gtevlublnu.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtsbsqejrq.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtpyarefyj.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtzpxvmnrg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gtkgtljqxz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gtdcqufwve.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrmwdbqu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtwnjreega.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gthvjkenwh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtezfylbfg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gtavaacrro.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtdisnsgqx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gtkigbuowq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtbaefzcpe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtdtqtpdvd.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gteyaatvfo.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtgispntpi.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtooggmdar.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdymuwru.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtgbabhjga.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtmabdbvta.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtxzpqlxeh.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtanrfrnop.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtnmthmnye.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtuoyfanlf.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnrdrtgg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gtrisfozje.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtuytksbva.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtrfsoqvtl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtqhjhkzik.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtlnosnagz.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitowpkie.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtjhudlfhu.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtdqdzkkdu.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtdxdzcqwc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gttacntchg.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtzqgpuhpr.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gttszjihkx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtpysedxzk.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtzxrjpujb.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtereqaqbe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtawmzgsrb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtrhputspx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtvmyjjmqq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtknjjqqfj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtitgydlry.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtezlqidtf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtyaqkinbs.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtcgctqevw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrghfouvy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtykxnvwff.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtygpxyrop.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gtkdeifwbu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gtpunuemfd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtfwelxmko.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtvtmfupiu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gthtqmvjri.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtcurzhikz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtljonaztk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtnaafklea.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtxznqozgg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtjentcjbf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gthpvhvdot.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtpbgqhtjq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtatxdfwbs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtddhbugea.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtoeyopimn.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsprzgntz.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gtxitnetpl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtxcdhrvvz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtyabyqhsc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtmuhkevuo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtfaztkskw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtoymxnlnd.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtxqzwmeem.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtlhtbvnhp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gthmkozguk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtmewesinc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gthxixudfj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwhuaxbz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gtkarxhgqg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtiezncxve.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtfcrfevgn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtwgwjjioj.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdqlxzrs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtqocthxyx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtkrphuwku.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtlmmjcnmu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtwtedtwvk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynrodvsz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gthyrnbjnc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtuurlixrj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtibrpzcch.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtsgatffwk.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gttiiwtzrl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gteijjeitr.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtogyrguyq.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtfculgaig.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gttbnlqpvo.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdacqwaly.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtdjnaejyj.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtcymrbnul.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtbiuogvnc.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtkipipsbi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtujbnfvef.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtmziunhie.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtajurjuwr.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtrithaqep.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gttxhmfern.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtcaswomjz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gthdudyqft.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtygxvupae.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtrzfgjkxf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtnfcvzdju.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtffvgosqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtqcmdzmpx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtzgzpepkm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqvfqzos.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtbmvskguj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtwnrcsmob.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtdgudvjjh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtfblkrpup.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtarjtxqct.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtpjancdfj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtjvaywtrk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtrhsrdqff.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtbvlsezgy.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybesjsga.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtyfpefjgb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfcmnncie.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtkubioeqn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpxcgtbus.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtibzrcmtc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtranlopjl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtftfvsand.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtccjyrntg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtaiayaovn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gttyzisiwu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtsxwuhtfk.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtmnrauzdh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtszvehmaz.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtfiuertbp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtcbrosqdr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtyusgtdwd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtizhvruqh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxivpexep.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gttetaruqs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkditlpdo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtepjqvhwu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtgzrpnyjj.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gtfaupmldr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gtclivxtsc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gthbzbnudn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtceakyjdt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtuslvigbd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtsnmowflu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtddohjgnw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtiekdaxlr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtxfxxcfvf.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtdyjqbkai.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtsnujivfa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtlmntsoir.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtuqymycxk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtcwyhqwan.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtdcgzwjcn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtlhjtmoxm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtesrznpec.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtxifpsepa.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtbumhtquu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gtikjugdsn.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtxybeazfq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtiyyxpnzd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gteplmpxhl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gttrdkpwzw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gttnglfrom.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgpuocbrv.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtekqogfrq.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtrmksmmsa.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgahgwnht.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtvpaevmif.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtoawvrdnc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmhnyqqtz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtubmmgnwe.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfglyxewh.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfyzerubl.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtnqvowgol.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtpchohkbe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtnkqucmot.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gtyomnqdvu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtojcacyrb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtztjcekic.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtwnlkfpfu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtoxynhbkx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtztjxdtch.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtladbmvqw.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gtgkqzoasi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtniplkvcu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtvyynxtor.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtrdsmqtok.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtabtbtstd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtmzxxclhk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtmsromkhs.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtraxutrmz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtvmmblhro.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtalyjrwtq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjhfrkgue.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajjamthx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtfcmoojxi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtxuwkenao.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtixqxcruz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtecgibzjh.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqfnjseaz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtajmcikut.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtmdewatyq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtiwaljxcx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrgnmkpzr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlhlghvll.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpkrmexyk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtinlnymgj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjlhbfixw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtygliejwi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvtwonlco.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gttheqwjkb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtibqpllxk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtlcqdgmqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtamroqsng.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdoglxpqb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtiybvefrw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtukszatyc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkvrchoqk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gtkpozqnal.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtluhajbyw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjkkassr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gtwnozries.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtkkdywfyo.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtjxuqkkba.html


<!-- 参考信息 -->