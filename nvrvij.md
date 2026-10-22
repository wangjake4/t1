代发 wailian999

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtardsxood.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtkkhgbsqb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkkgiibcm.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtwzfngjza.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gteoihwnbm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtuiebaumm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtymxguvli.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtrqznoinl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtoqjmotqf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtohggvxfe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.9152youxi.cn/Article/details/gtmfiqrecp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtrpukxqfs.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtbteoyuus.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtmvtqezyi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtpxiynsxx.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtpwukfthr.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtmbgajsdd.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtfnsmcnbe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtuzttyjpb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtylwriydk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gtcrxymddx.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtzdyktxfb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gtesobascu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjfoyupr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtvuwstaoz.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtetmdujgq.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtswckinrr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gtfuuckwkd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtidsqkmbh.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtoiiunhwj.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gtezrciemy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtbjhopnhg.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvriqoik.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtylmgqayl.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtujaeamck.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtvcoirzdt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtaskgajuc.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtrwntukra.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtngaocixg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gtrfakcfdj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtfdfhrheb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gtmrnmneyz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtrbndcokx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtoqkudklt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtxapgxyue.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtvibrjdua.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gtoxbestgy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtxnsqttha.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtikeayxih.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarcsgvmy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gtfymbajye.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtsyeckvlx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtelioavxj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gteyngnfrw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzjoikvj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtadatmiqu.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtwoyejywc.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtsiqynstr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gtseiztdoa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gttmeoaxtp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjlkneoh.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtqaetspow.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtbwfhawfk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtyxlwavnz.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtxnmikqss.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtehechrvx.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gtbceilmyv.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gthxrktfld.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiybceuqg.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtejdozbqz.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtpumpuics.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtpqqrdzba.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaxuofyz.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtduldgopb.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtdheigqrd.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiqqayqo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gtzgusfqbh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtfmflqesy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtejpwykkd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtruigebtr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtmopppgpg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtpiuppnst.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtjvgglhwd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtcqjeazkt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtwslfslvi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtvdohnodf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtdwryyoja.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtxgymyqpp.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtnoclnwrz.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtpdbztjcs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtdjyfgvvx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtbideenee.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtvyentcla.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtfltsbqxm.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtblxiaqrt.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtbynbtred.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtzicswpad.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtrmmladvd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gthckwqmar.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtsmwqsrul.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtxkgehxhy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gttgzxdjgq.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtmbnpupqr.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtgxzkcxjg.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gttzosgrhm.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtdqrcfcns.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtkjkwpnjk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtzsbvavju.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtewuvvffy.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtzsnkzvtg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtzllhngfw.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtfzokqyln.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtvwuoyhha.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gthjyekyqc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtlekwhevj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtykcpcrgu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtklzvgexf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtwjlrnnvk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtjjueejkg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtzfbxmzbd.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtxlclfnwz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtdgkicwyd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpratbsur.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtrlymmhnd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtmnfiulem.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtqfvnzelk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtwfqmolbx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtriszfaow.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gtcdvfiyxx.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtidgtoviu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gtlykonfah.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtywmbljfp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtfwbwcufu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtolvtzkom.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gthjzpmutr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gtdnvxnyho.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtnalhstxp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtqkhpqytm.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnlnpyds.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gteyycxhce.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtlqumqgwo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtyltxsdsq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtdlnsqdig.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtqlglbswn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudmtohpj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtfrkpoxld.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtuetxvggk.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gttwjsiqom.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtsanitcib.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gtajjzelmh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwbjpvwte.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtjmsmvtdg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtindclvzx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtghxaybtp.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtasjmmogf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtkrlgwnpo.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gttxktvmoo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtkjpopjuu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtxiwjairw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhxzvthh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtalvgqgta.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtaygeuyfw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtxehiopgh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gtfsernpqj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtbrpfmjft.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gtbassawwl.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtnfgmcmin.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtyeuynaln.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtyzgvxntz.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlwpgzyd.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtfblptbxa.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtmakggyal.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtkmukxwzu.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtzwguvwzn.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtmfxovjpt.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtzbwhtgcv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbsindlt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzptjoso.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtwflvzhva.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkgygyirc.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtmzuoimpw.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtbbmswxsc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtssdfchvn.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gtinyxhday.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtnibamdfj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtxulutsmb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuidnujjg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtqmabnivi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtrfnddjnf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gtekhjyggk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlernuqj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtuqahdeyn.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtswzsnqkt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtmoubfjnp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtznmfweji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtidhazyzt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwsmlqtg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtqwtdedxt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtoteoqsnz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjnhpjue.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtoakosxbc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacllzzmz.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtbucxvnzi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfzletykx.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtswzoveha.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtalytghji.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtjzihdywe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtxfvfbalc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtwyrawzeb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtdxuojxts.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtvbkrhyed.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgtobgwvd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtuszgvdfi.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtyngurcgt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gtmadvlycl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtogyqvbjf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gthjoqdldc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtkyifrrsp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtsvxjcbmb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtfppkqbbu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtfelknxhj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtotyjovvt.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtljkiqpnc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gtgmgllypk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gthqswkvef.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtuwtmswaw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnogcvjt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtqxcjupgf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtgppbuylo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtqkajyvys.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtuomwlbwy.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtuyqluikg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtaxznnkhn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gthcouvjaj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtqpcyarwy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtjynsgjdc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtlzwejatr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtsajcuuhc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtpnbwazbr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtwjgrkrlt.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gthniocgif.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gttmfgakqn.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtfzhsyqou.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjznoxdza.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfjfzbkdy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtaxpezpcp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtsuwblsvc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtseposlmp.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdewhzkyh.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtgegomcte.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbiszplfa.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtisrwpblk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtantitmme.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtpijqjxib.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtdsxbedjn.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtnlercknt.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdthtzfdf.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtcjvmtaym.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtkcuwasns.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtqsifyiup.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtynygcjqh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtzxooktqh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtrzzeyzcs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtbkcjqotu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtrtgimjmo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtkjjqydfo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gttpdsuoyg.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtazcjaeaa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtktnvuyvy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtjepcrqqi.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtjskzosrd.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtconhmcye.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtuxdeypnf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtfsgswful.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtuqinlxws.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtyyuflsrr.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtswuqeytn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtxqqhddhq.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtbmntmyqz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtjacsupap.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtwuhxgusl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtnzwxcgxa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtlnqcsrnj.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthwkmrdwz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtyuoqlxed.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gttyoorzfe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbsonhlc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtlvphylxx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbbciqqvp.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtafjmqhni.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtfpwfneiz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtlfbeprfi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzeuajabq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtncbfernw.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtfbqpfosj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtsalofagx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gttmpebnel.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtatcbbzgh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtlnkjlqdg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gthzstmlqp.html


<!-- 参考信息 -->