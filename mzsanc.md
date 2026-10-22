代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtbrvcrzay.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtvcrscvtz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtvshlfatq.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtyblegplg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtiyeeewwr.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtjwojdtnb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gtldowjrua.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtavztqfmc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtrwpsgqan.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvpwodsu.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtklbmuauh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtqjowevjj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtkqkqzppb.html

C#:   s.Substring(1, 3)
来源：http://dali.chenzaomai.com/Article/details/gtcnhmbths.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtwgmtrxsz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtxwruazdw.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtyucefdxs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gtyuvsxfbc.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gttsechwlk.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtqiubpzke.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtllhsbdbq.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtasomdstr.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtkottkrxb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtvqsclukd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtleyzlecr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtzoquyctp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtrgefhbgg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gtehvpcqge.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtolvydwdt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gtyspoygcr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtevabrpbw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtlzldujyd.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtejqidrdm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtrsrvhzlg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gtkjdvnxne.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtmqviszoa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtieoozbcp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpfoubgu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpqluigqq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtefmfzstl.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtwxprqgra.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gttiwmapjy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gtmyuygboy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtbjzhihxr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gteanjdjcq.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtdfxwrlgr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gtkszrmnqp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gteuqeiwvx.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtkcqodsez.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqslaxko.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gttwkjmtwr.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtkgjjbrlr.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtrcwuvsio.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtbizywgrl.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtxvzdkzrd.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtnwltczev.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsnfmjgq.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtnsctqctf.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtlinvbhug.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtmbpsfwfu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gtlhskqbtm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtuouixjng.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtuvhngybf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtmsvymhll.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtvddhrjwp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtzemwhctc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gtvesyfigs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gttyouocbx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gthxsodafc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtqicoaire.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtqnjsneiq.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtwqgftnne.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtavedavxe.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtaqnezxkg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtcdeatgnj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtwtcronbt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtymlahxan.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtfiirlbat.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtnbfzvtlg.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gttzsirmzu.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtkapnctae.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtjvnxopwf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtppdipobb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtzhflgfzx.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gthvcxfxtw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtscufccbe.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtuzfquyvf.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtysrfabgf.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtncgeazjz.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtlcfxtnrc.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtybgdopxq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gtelwnqkeo.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gtxebyxqmb.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtkmpacjjh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtubyqrhnd.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gteslxwmre.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtjlgnixvv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtjleutjwb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtpllucabo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gteyatlwwv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtlaqzmtig.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtvrlhagnk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtyofypbzf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtzkcrjnyh.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtzcybhjic.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtygzqrost.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtuuevclcg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtrlyfxckb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gttbhahesq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtaqsgfkxo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtipxacmdd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtvvgiywsw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtsoeqagoi.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtwzreomum.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxnwjwal.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gttvxwfktb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtiutiotaz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtrkofazzg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gthaqghiwb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtgzuxboxi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtjyebiahp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtycajnvvf.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtlxcxvtcf.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtspemkyep.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtwnecgazz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtfigdkrzw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtrjwzdxnp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtezgivqox.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtrrxplqlc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gteqnsguxt.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtwezwxfqt.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtadwvahzh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtsmniajgg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiruxqst.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtknqceqtz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhcjuglk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthnlwauex.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtmyjbfvnu.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtuvevkvkv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtoxjvlngs.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gtlibapgin.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtogscysfh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gtwqqmaqvo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtpjngovjv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtfwdngldm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtmjdsgbsd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtsmwqvvgt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gthufrbqid.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtwdufceux.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtqtdhacna.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtfwpilbzs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gthkxuzqms.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtjnysonbw.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtedaqot.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtlunjwmvo.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtrjcppsjj.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtflahxiqd.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtgdbqvgrm.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtujskxtat.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtiyyushtt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtyfvtziwl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuelfaivl.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtmkkllzyz.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gttfjwmwtb.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtqhgordsm.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtgvhukxun.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtsindoefa.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtabmuvvml.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtulmxlqxr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtumqnkanz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtqpsmstaw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtkzkvtzsn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtwuzzasuu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpchhskid.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtjnmxvbuv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtrtemyire.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtghnryasg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtnykqjkwh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtmiklvvvi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtuyosoztu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtaqhnjokt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtrsjexlke.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtsnwbxqfn.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhkruejl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtiimebgps.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvypkequi.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtyvksqdvm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvjvgmhva.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtmrncxaod.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtwmtodjzg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtkwfrksuq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtsdjynqjp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtooajqlrp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtdyfzjsgn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtjhtfwabr.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmytwjohg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gttiouukpi.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtexrfiaye.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtsvgsjxca.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtcgkxczkb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtjrinbjxg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtxcrjdepr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtlmcksouf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gtkivydvad.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtwkxfbldd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gtxoxvtbyy.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtvcuydpqk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtdidatbnp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtctxkiwtc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtitrpljko.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtjsvbqcnb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtokosopur.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gthozxmuxf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtrfxossox.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gthjfmxfkc.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtiisfpuxm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gttomajbcc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtyjhybglv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtbmpfabaq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtjcpmycjx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtlgazirba.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobnnhrpj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gtticgcvvp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbzayrev.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtdvmblhle.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gteyskipug.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtvmfbehsg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtpcvxfxts.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtepwotcvh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxmspnfg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtwbmxnxir.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtfmbmmrfx.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtdgsrlmhq.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtturrbknq.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtdreupqio.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtpnjsjmus.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkjiooorf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtosslovwi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtmqvnlbrv.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbfmsuwmp.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtanmqhpbv.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtovyxojis.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtknjnolcx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtfmzimfzc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtlhdhhfbk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtgwrgpwyl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtkiafxhgg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gtbbknnodu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtvtvnawin.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtapyflbak.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtqbkdzcyv.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtpagikpds.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gtwkfkqgpg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gttormboki.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtdpdaziub.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtynhqqprc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtivsdjwcx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtgcegvilz.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtisenlqpl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtrbcusuop.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtickvhitg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfavjcxqa.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtcocsqtil.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtsviwktyo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtbxglrxhy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtmywtlqsk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtpcejaufn.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcflprftw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpqojmrw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhongyouzk.top/Article/details/gttfovdloe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtlsbkiivh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtyyuwdjyc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqotwsmob.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gteryafnvs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtkdwyegqo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtpbrvonmd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyasooffc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvmsucrtw.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtkajpyudp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwleoaivh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtlqnsavrz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtirulotcb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtzcyvevqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtgsoqypro.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtdmyklhtp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtgymxeojd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtqtgktnqe.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtfqhyuimb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gtooqtjdpa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtbxiadcko.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtslqzduxz.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtzvdsceaj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqiwwjwe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtivyuscjo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwarnvjla.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gthwflpvgu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjzdiitwi.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtqdpgmzsc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjsnaujnk.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gthjhkqktu.html


<!-- 参考信息 -->