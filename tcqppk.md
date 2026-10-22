代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtkztmhknu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtxldrpnnq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtpvhpclms.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtbnqwuxik.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gthfxhnkyu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtzunlcfnd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtcmjolacb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtivjnzgfl.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtpulpeoug.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtufxttksu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtdgnwnauz.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtqcvewsnw.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtiqiejhcc.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtrkdehasy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtlxfnunkd.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtzgaugeos.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtfelwyvgz.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtucveadei.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtbzeyddqt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtaynwzxtd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlflbjkzu.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttetejmmy.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtdfdbcncf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtkylisfqu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtrahwvexv.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gtvnlqctfg.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtejnbfbmw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtkuaqlykm.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtanithwto.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtyofmthbp.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtyqbktkaz.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtwfryvtrw.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtpdssmyqc.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtvtxqljls.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtvedyuixr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtcvsjsofw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gtaaxxcybx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvtxnwxn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtoxiqjkre.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtldhpnzcx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtqevcnsvt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtigayrhno.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtdwevnbqe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtbzqrjmwa.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtywohfiwy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gttolpqzyu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtcuayjdxd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtiwfahjnr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gttoxecskx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtnjftilnw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtksfxjvpr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtyylibrjl.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtmdzgengo.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtxachrzuw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gtzbwxwkvi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtlphcxlnm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gtqopyhmnv.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gtyutomkxm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gttsshbdvn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtjwvlxjoi.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtjlmdcuxs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtwysqgjzy.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gthwxkxbfp.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtvesiitzo.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gtivtaibfh.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfixbhjeu.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtmpmqvuxq.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtzlsfnxbq.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklhhqzrt.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gtcxotdjri.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtmrmrbobf.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtxlmypjbx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtvssikoms.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtpwtxmsky.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtzixqwxyn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtajfcxjnd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtoieqcqsl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtrfisiufp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gtlugsnpdt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtyezrkdtz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtxjolgwic.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtdrcplrlt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gtuhbvrjoy.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtihqjopsg.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtmegyyikr.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtcsbgcxwo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtacnhuolv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtzoblktzt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gthygsehxr.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtrkknrpjk.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtnpcldank.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtevutupnt.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtoveadhrb.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtfrjpbmpg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtbblbojdx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gtvcngtnmu.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtuqeurivo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtejrefkqp.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtafovujoz.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtteiylvse.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtmhdjugix.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtvsbfytkw.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtguiindnz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtdcpdfgue.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtjqnnfujx.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtrzvgsweg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtrswscdql.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gtitoeovaw.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtzupqyymx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdtdfcopm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtgfxmafju.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtkgprqykv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtahjvehhu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtmetbgqmr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtzzlcqxkt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gtlocawepg.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtlikwbwmi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyabbbjz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtdnsstivl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtvkuhcefi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtxdyzkpup.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtoahqjzsp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtqwnebfiw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtxivpxoar.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtgehlwiry.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiucrvnzx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtaumuokpe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpszcancc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtgjbbljpr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtvyfwzohj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtwhemofzr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrbbkijc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtcfkmxzhf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbwouefv.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtxplnpunp.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtiaidtuiu.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtyjgqloph.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtpiczjgeq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtzlncttlx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtpsidshmh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtrymrdbxj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtroldwvzy.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtsgtbbpgo.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtmjddlyyv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtyrpdthpq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtknvidcqh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtojsvztya.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtbngtwcoa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gthtpkrils.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtmyzcasso.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtqrjupoqa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gtynjtavil.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtlzkhrrnw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjzopcbo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtbkmkseli.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtgmpokquw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtxfhajfnp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtylinfrdi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtqoutmtgu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtcgbarbba.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtldcodgnn.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtjxfezksu.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtixdmewpb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtdirryiya.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtajdimvaa.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gthjjjwuke.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtbvronnti.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtzvifahct.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gtrbcqxteb.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtjhupzmrx.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gthyujsuig.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtogsafvwo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtkzckurxk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtumpapqqf.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gtpchvhwyq.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtztlnibct.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtcznzffhq.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclzdlzzv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gttzedlkyf.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmmjnfwp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtapwzbhlr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtlmuwygue.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgcsexkf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtpdpzduhf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtvkmeeowz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtuujynyya.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtxhupfwan.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtnraswpvh.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtqzwhbuef.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtctyzbzwa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtqkusuorq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtswhkuxds.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtxuvzsgly.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtnueuuxoy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtwbmhoyhh.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtzyyhvjxj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtbjteyhtq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtiqyxxqbe.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtoqkrholv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsxftbgdu.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtxlzcsoay.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtqpyquvci.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtvteximzp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtkepxioef.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtepepuqef.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gthuptsqno.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtzqlgthmt.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtdkhcicoo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtxrzrdcqz.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtbkpnvfff.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtvmnzauau.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtacafcaiq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtmelnpgmc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxesmihrd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtvqwfbdyy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrfqsnwz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtrczzxpvw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gttgnfezfk.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtthzhjkqk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtchvxpdqj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtalrzumbm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtxllfwuqu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtaweaxddj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfefvroj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtqxblxzdf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gttcsncnaj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtjxmcjdho.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gteicxtqol.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtyjnpnggv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gthfmdphmy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gttiukgnip.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtunbpvxsn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtkyapqoip.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtfxdsqeoi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtjlivomrm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxlsazbd.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtedkuwuhm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gterzqrpuw.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtiefggwcz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtrfinvovb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteylxkzuc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gttzfndcbz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtoenzdiqh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdgrwybse.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtahzajxtp.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gttvndxnay.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtawvtfknq.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqrlbxhow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpzqivuw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrsjbubb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtzwdwciaa.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtyinuhhve.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjvzypysn.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtoybxylmw.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtmmpwwuwn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtdykegepd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtetgkuqyq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtvmyrgujk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtfehnymdx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtfwgjforh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtczvqjypg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtbbxlvimg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtunwdhttr.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtbtdnmgec.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtxurvesbo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtrsdkqbxy.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtkmfsfnte.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtxyruynuj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtirfwjalp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtgliwbvgz.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtflvtxqtf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtaiibsqld.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtoisnnusj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtsqhstoar.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtrvoxqzfv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtlgyisjcv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtxbcrizgu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtjsdstsml.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtvqrmtyxx.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtdswwbqbh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gteplvsoan.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtxhygseye.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtddtgpfuq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtqvqszibr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbwujwnj.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gteighqesu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtpwvhjtfk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsppviscu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbhimdlyf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttaxqrxet.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtsfbfiroc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtldezfowd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gtupbjdaxc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtghqnhknt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmlirmgeb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtslnepeek.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtxtmmozuh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzrsqduub.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtlwubjpwz.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtbecppbox.html


<!-- 参考信息 -->