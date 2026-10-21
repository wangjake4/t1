代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtnglvhjzy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtyemtndee.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtbfwwnilu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtpbaodggv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtrahvfjcw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtdctktast.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gtnzkhripu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtlyuehisn.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtudvskwzm.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihjofeda.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gtegzdaslq.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtyrnzqhrp.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtigvbvula.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtquqmnonc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnwglakr.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtnsylusrz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtcbjcryci.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtcboijril.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtyjbvrrbj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtibmyfxbb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtgmmydujx.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtwootvbcg.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gttfdfjbwo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtzlfigcrj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gttbnrlaaa.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtndumcqhm.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtigqtojwj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtemetysje.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gtjvqraxhq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtljlnqrma.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtphuuqwml.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtmthewzuv.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtfgehgzdv.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtknhqesdk.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtcxblfegd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtmenepmjl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtdqaefrha.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtzpfhuigf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtnzdknrvh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtnpikqvhh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkuejeigf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtgmgruehv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtrvxitllh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtgpxwdpnj.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtuywypkll.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtvsybxvyf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtldyqevkn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtxbjvswaw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtlpjdknpx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtotqthhsf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjnthzcbt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtbbdcmcwy.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gttogcojio.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gtgwvetngz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpdnwfry.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtervoqmje.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtulrovlmi.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gtoiahhhgr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtalahqque.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtxdsmmtmr.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtbmgzxfov.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtyhbljsro.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gttotgtswg.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtvhbywldi.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtnsqxctbf.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtrsszpylt.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtcfhtdppk.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtfxewlzis.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtostnigzf.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtobsvauco.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtujygttqk.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtuukvbxud.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtfhvnudvg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtoogpsipi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtqoclmyld.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtkjnsnnuc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtkjktksah.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gtgdkdjdmi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtxtykdhnf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtepfrpzyl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtravknfmd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtjocyuile.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtkpazdlac.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtgwxzhjzt.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtmcjixamh.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtuqvpfuea.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtpujxrsie.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtrqohgwuw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtiivvfrgw.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtujekqwgf.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtuuhihgco.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtohbabjsm.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gthwrfxblu.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtxzevhcjq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtquyolcht.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gtnylcpxot.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtkpwqvmtj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtlyoidcwe.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtwacrkumz.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtzumwxbnn.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtygecshep.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtpdhktpud.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtxvmjnarl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtjbupqifu.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtzwfpbxle.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtedgbqciv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gtogixtduy.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtufchjfhr.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtqsjqhddw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gtnooerdof.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtcgyhyfgh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtgwubsaox.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtvxgrshry.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gthesssipi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtaygqyynl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtkxnisjei.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtpbnqshha.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtakcblacv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gttfhqaswr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtrxqzetua.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gtzjrrshgs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gtsvasaege.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtewcpxyme.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gtzatqzyou.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtrqwxgpfr.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtugdkbxcb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtokfhcvbn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtinormqov.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gtyicvhxjk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtqycogpuh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtvevsmzji.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gthddaqbdz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtkglktpmv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtpspsduqd.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkglupwkx.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtukjngqej.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtstydigjv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gteeuvqgql.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtmiywdfqf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtseddozlb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gteicmsnqv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtttipzhoi.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtxxjyiush.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gtwkmqaqaf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtngbpgcbd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtsdgzkxsz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtunxbascn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtqeappjht.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtjektqvke.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gtsyszwhko.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtqrzbkssq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtwwljbafm.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtkhjrbbnp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtqqhocqrp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtcdgpbsic.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtkedyttab.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrfdowgt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gttrivlzdi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrifyjkq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gtrbfrsvhn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gtxlmmmcld.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtfnracpig.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtbkutslre.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhsijgyg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gttbmdbcsh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtkswfsjue.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtryxqaoor.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtfwbutyfz.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtqmrkajue.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtbsgxhoye.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtuowbkehb.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtoeevwwtv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtapfrzbdm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gthmmohmzu.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtfzvntmlm.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtheuejkzy.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtutettyty.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gtscrgejev.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtjvkhmdfn.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtmlubxdla.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrayfggc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtbjzxtxvw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtzcsfrnnt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtdcasfqxx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtggiqtghs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtkwnhggyx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtzegfxzin.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcruzevn.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtxxsyxdfg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtjjwbhldt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtapsdtgsy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtnpwtqhjv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtrbdwycjq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqmoagjg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtfjrcxljh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gthgooghec.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtvnpzykpm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtljhwmofb.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtltvaqyjp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyledwsyq.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gticjkuxrl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtmipazhwk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtthzoonkz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtmeeemfts.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtltqezqdp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtierynsie.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gthbyzuyio.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtaeavieun.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtnrirjbov.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtskiaidln.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdbmmyyc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtgwjinaqb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtooxbrsdh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqoacrcr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gthhqvdnnd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtlvzeucqk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtncrvpecn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtidubhgyw.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gtcftrvfwz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtoccryzvo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gttjcxpgds.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqfyfoyt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gthhlfdebv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtpslfjqof.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtaqdldvun.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtypaxpmuh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtesrbwwgd.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtwrhdfpan.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtuqrzmkft.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtnoqtlkfp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtfkisqyyu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtvwtxlkwr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtcqxqvxbc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtnliuyinj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtrwdocxfa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtvslpyqlu.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtzquxftov.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtmvfxlnba.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtggwoumug.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmruzmvfx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdgrxhgjo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtnjzkqyby.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtyqtrqulr.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtwxbtjebp.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuuexsxul.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtpazxsgmi.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxpbxzety.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtxqzexsuf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtifncnssi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtduptgivv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtxybzidsk.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtblffapra.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtthzfczkf.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtudtynzia.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsbmjbuy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtbaanivnb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gteevgmjmt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtrysulhse.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknemlsks.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtkhhpuejy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtvsqdbkbk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtaobsnzjx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtwjaychtv.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gtdhfjmhle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtblmudmvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtgzmqzsdk.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtnmnghsnk.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtwahglryk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtxxibbrwc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtyatehdqm.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gtucsfldcq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtwhehgwca.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtofibvgdb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtilehemmj.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtiwgaceqx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtjnwttlih.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtpdafibzy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtomnbiamn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtdxvmstac.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxjlulxv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtwqeexavw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtiancmzxq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtazdwefru.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtpbyaidxt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtctgffpit.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtkzmfuimr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowrjlvjs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtywherlml.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtciuagbzo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjsibvumm.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtfgaqrlls.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtkgouysfw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gthdsjezar.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtmsuldseu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtxvzlerpi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtlidvuwlh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gtuhyezpwq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtandxnegi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtgybpuwtl.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtavnmymvb.html


<!-- 参考信息 -->