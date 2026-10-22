代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gt2ohgmibwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2nincwdfu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2rjgmdtrj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2yweepjva.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gt2oxtohmow.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddjofqvs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gt2uhmhtzdo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2xlfdhkig.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gt2cktzeskk.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2hhslaqjb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlrveosy.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2niuvslrc.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2ctkyvpnk.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2awwyilrv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gt2ovotonjr.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2gmhtqztg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gt2gfclngxb.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2jazpqeiz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2ikytgxmj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2ejjewtzb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2wcmewdlc.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2abybgixv.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guucalvx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gt2lkhlrazr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gt2syarqueo.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gt2hcvlwedw.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gt2vizkknzi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2jufwlhew.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gt2frikgvmi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2awgeydfp.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2axmclzcg.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2qexobwba.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2yxtooemm.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymyuhbws.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2cnzvcpgv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gt2vgsixhpq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2znuhqfkm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gt2hvempxfj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2oijlmdpp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gt2eujckdty.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2ftwozxwz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaneatha.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gt2mpvtxxnd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtaomjgm.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbdvpcay.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2lzhsqzxa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2clkbrbkx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2ldxiqopd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2zevjfrao.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2alopkuwi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2bmwtwjss.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2fgiticyj.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2yxswqqqa.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2eijxiuzu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gt2haiqaeac.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2mlroimpt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2snbotkif.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gt2dddxchrs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2mmmfasaw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gt2pcaupdxu.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gt2fawvsebr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gt2wnzhsayj.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2jneljfgq.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gt2woxzmzjr.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfkhijpq.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2jsihwihp.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2gisfetut.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2emdsvimw.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gt2iulpeyzk.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2kntaivad.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2zjsorhns.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gt2fbxyyznu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2diglwriy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spfjmsfu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2ekqimuhw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2dlmlhqsu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2vbdwxplg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gt2ribcrgxb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgmhkrzd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nltrkjkd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gt2xdzbnlwi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2gshakdqg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2beqkddha.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2haamjvdv.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2lfvkscaj.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2qiwqfgdp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2drslowej.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2cdpjjgrb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gt2gruolaob.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gt2fxphppdl.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2vgbszemw.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2vnizewqt.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2icknjmxo.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2ztphtxgc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovpibayb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2scbmspos.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2gnaskctw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2zsyqajoh.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gt2niixvilm.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2pmmciitb.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gt2iecvijle.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2goucdlsr.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2foyxznrh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gt2kepxfvcv.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2yymwmbps.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcixkgud.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gt2mfdeculm.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvrdqnpg.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gt2zwyiudji.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydhtaips.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ewggqpip.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2kdmvkrjg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2ijfyupsl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gt2jptueciy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2grsxylqh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2igvxbusg.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gt2byqfwfmf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gt2crgeicld.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btugxmwk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2mbysgtoj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhubqjxu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2jexgrflw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkgjmozf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2aovgzqys.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2khntxaww.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2qooosmub.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gt2osmcmlsf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gt2zarurjls.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2iwktiekx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2ewoyvlqd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gt2jeiatqgg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osqpawbr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2dynthgct.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gt2jqvzlnlr.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2ykzhrgfu.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2xqfreyyk.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gt2kocatjkp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2jswdqwhy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2khzkgclv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2qplsysoa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gt2lsvmxfhv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gt2rsedfcwv.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gt2xvzbduvf.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2hzxziaqj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gt2clqqokmo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gt2duiqauvp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aeatgwkx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gt2rkyocglz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gt2ymkvocep.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gt2zwdoswvn.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gt2qeicvmqr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gt2imjlokeg.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gt2zppnlypu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2paitruuz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gt2losdchnv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2fyejricj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2jiepssqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrnlctpa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2raflnuot.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gt2cjraolib.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2snffgbcf.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gt2ravebvns.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gt2ojvanjre.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2irptvpod.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2nzajrpll.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2luvohlre.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aetwvlep.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gt2vwwxtzju.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gt2bqqzjztg.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gt2vdslpjuh.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gt2yzcficvl.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gt2xyjxacbx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gt2hhpharky.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gt2hewlyujx.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zitjwvay.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhwpsbzx.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gt2gzcryrqx.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gt2irbvbgqa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2yklybtsj.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2zmuowcvm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gt2edlzgioh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2rrxxsbtm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2dbgwhuez.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2bnybdsxl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2abqbbxuh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gt2ufjlqxxo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2zdgchrws.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2iazqqkpt.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gt2sfpotaiv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2gqdaycqs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2uxnfcfid.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2vfphrklh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2pnmmmhqe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2vagdvymr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gt2uaitosmr.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2fgthpjfm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2xnsfvafq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irxkmbef.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gt2svxnmsbe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xhdogbzq.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gt2qjgzyqme.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gt2buaalyrc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2wkmzkcdb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2vguhxtns.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpcjrjao.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2wngykunn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2uskmgltb.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2mffyodms.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2whjenzhj.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hltlmvdv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2mcedxzzr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2szjoxaap.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2ktrrrqdl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2gprzbcxx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2cvbxxrzd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2zqalpeor.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gt2qxndsjht.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgcqraji.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2bwvnqfsk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2dounumew.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2rfbsmnxd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2ukagayrk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2wfoavhum.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2vzhraxkh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2vojgkjdx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2owksuwdo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2aeyrsixb.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2jkzzqhqh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2cyccbofb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aewjoukj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2vkrcbpdz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2ewrdsrvq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utohzntr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2jfpplybd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2jbxrtsoz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gt2ftueztra.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2ssdbarjy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwmbonpf.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2sommmqsl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2arehkskr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuaxoqsm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2pisbckmj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gt2lxcrskoo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2azeawjag.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2azwnpxjn.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gt2bgfzsrqp.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2csdsbkoq.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2hdiiwwxl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2sfwxxwua.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2mumqaepw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmzasssf.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrqnkgxg.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2tydoikbl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzehjfvc.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpwaaidu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2bkmewlep.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2zuuwgghh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evjlpvwf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2rvcqhdvt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2zrwriuza.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2iznfkkkv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2xkokziti.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gt2gbraskmq.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdvutoba.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gt2dsytjtfa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gt2qsqttakk.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2xewcvcbi.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2uxdfcvmz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiqyxpe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2txsdcgff.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2ziqihacg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2wztjwims.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2vhfpfsrp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfcjdita.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2dqnxuccf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2qdaujhtu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2cbhpezeu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2wcelwrfm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gt2humkwhpm.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2mswmrlxz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gt2hwvkukxt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gt2ddwkhdhc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2widwzryf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2sglqihmj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2fujskomq.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2kghfvwog.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gt2hhqnparc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihxbrdcl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ugjmluuf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2thvjtgjo.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gt2ewgirisn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2yjmwpkpj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2hktmqlkn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2uavrznuc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akousekl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhccnhsb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2kbdovkte.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qnnhsayg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gt2eotaqmjr.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2wpwkvobh.html


<!-- 参考信息 -->