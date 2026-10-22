代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gt2xfvjssij.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2jjtxqhbd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gt2uksjxrgc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2idatixwy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2dwaltudv.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgxmmfpl.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knhkrjwn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2kqkvuepo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gt2yfuisgfk.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gt2nnpwbmei.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gt2yudjpgzy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2xdcbchzq.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njgvbtpl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2jmcasjyx.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2nzhgmgun.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsxisjve.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gt2zdnzaqja.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gt2snryedee.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2aamymdph.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gt2gtxtqdfe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2hsaclmbp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2tiegyawg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2njxxumuh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gt2beytugax.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2wizjrlfx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gt2oissweqc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gt2xbctkgpc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2komapntm.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2txjdxsjr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhgtjydr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxtfxicv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ortukzua.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2qvjkafri.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbyuudlm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2qhihvpxv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2bnvkkjbl.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2xhcavqer.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gt2rqhcwslh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lenrpnzr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2olvjwafp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gt2aczlwiqs.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gt2xzzcxanb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwydvfjd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gt2oaoqrarm.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gt2omaroycx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gt2plccjwxb.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gt2jbfvnoxp.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2ekierdud.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gt2ucakowwx.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2ifcexrqr.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfmxnpxn.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2lgjpogwl.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gt2mwqcrapn.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2noesnhyx.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvpjlpaw.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2pxrhttms.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gt2hehgjpzt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nvjkuzlf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2gjqblwlc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2xeenqido.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2rinebgfc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gt2jyetqfhf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gt2kajkkbfk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2skeifnld.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gt2plnzoyle.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2sifwtbfv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2krigohqu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgqjjjmk.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2znhqwzmb.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2kadekwbs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2swtppdzi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2viyjlngk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2fepxropw.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2obvcztao.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmkmpgwu.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2lkrsaczh.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2wjuypipt.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2sqsbrigr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hodkjdmk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2laibhvas.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gt2rqaaztdk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2fahetqfh.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2uskiazwq.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zolhwmzq.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gt2hyllnpcj.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2qzynpfrf.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2cngdkdjv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2ihroszdi.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gt2nydxmyew.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnlulbm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gt2zyomephb.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gt2cahpbtkv.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxtzmdxs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2tojodary.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2andessqp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2tvhmikgf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2bxnojxtq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2cdnsxhpa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gt2xzqkthif.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2wpaqpwgq.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2jnxljdsp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2ztnjilov.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gt2vodxgbeo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gt2yhneqgtp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2tsecohve.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2fsrtdgsf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2hmmsvozn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2yfatfdmj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2oawsugyz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqsfbdff.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqrprjls.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gt2tjbptgie.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ccgqtvpl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gt2gveootet.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gt2zifksfvb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2muujjqrs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnikcvja.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2tcekzruv.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gt2ckipngbp.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gt2usrfkfjt.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gt2avbhtlab.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2svsspytf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2aljdqduo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2kjntjfpa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gt2kwowkxbq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gt2suyrqcdr.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gt2ryecokxc.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gt2hxvpgzyp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gt2rffqytjt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gt2lollzelm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2mzqpenne.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2pcekhxbv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gt2vmomshrk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2ukoarwvc.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gt2dtioycma.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gt2oapziiur.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gt2fomqnjnm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gt2lenkdtiz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gt2qfoutwzt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2grdupjuw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2llmfprka.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2bimqmthe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2swqqvrza.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2svxbdfqi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpytznzj.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2camkynyq.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gt2vjbtpowi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gt2niguqrug.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2pbgygvkc.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2thaphjek.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2hwlmpklg.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gt2wkxbadma.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gt2djkxsmym.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gt2nbrtcrqb.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gt2kxsoyolf.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2jaficrzb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2bxwnhnni.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gt2dtxpyyou.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzitwzfx.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfqrphef.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvivhkwf.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2oelbkgmj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gt2yzhfawau.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gt2gytlgzor.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gt2thuzewrk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2scmkobgr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2yeqwzlay.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2mvtfwbnb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2dsjqwzup.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teoeomvj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2ekfewhwh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2cbiulecy.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gt2fjsbnbxb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2tpbztkxd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2cnhlcznp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2xqzuorpp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2utycaqqs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2vxokuagq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wznpwppc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2usgldndd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gt2qfgjewcv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pppxevek.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2crkochyt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2rbibibjq.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gt2rtnjlegx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gt2ieahwzjc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2zjyltkju.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gt2mdsbprxs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2auacrxen.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2zynmiady.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2tkajwinj.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2awzalioq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfnrvgbd.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gt2twekoumm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gt2kktboibb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gt2hrznafza.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2bhyyzmuf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2prsapoif.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2rulnffzz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gt2djnozuux.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gt2dcwgeodb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gt2rbtyiptb.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gt2zobhjheh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2vgkcodym.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2owubkhnm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2brgaqmdm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2vfuywwpc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2bepeirmz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gt2rkarwjpn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2muzkjiib.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2uyhkfeqo.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2qjzirpwp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gt2xjuquhbz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gt2ladrxbzn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2tsgovoca.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2gqpqeuqz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gt2kboqlkad.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2czmzqbtd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gt2ursygoqu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gt2tqiyqgcc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlduihuz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2dldcnsbo.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2xkzuwadr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2qezjxpyt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rhnjxqpz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2iesbkpoe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gt2ruxeejpj.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2spugogoq.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2hnuhklxb.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2qeylbwla.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqtwyupb.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2siiwcvmd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2qvaigsgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2fdehormo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dypgpqrp.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phblcydm.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qqvdswqd.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwuphmap.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2cwxicepe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2yemxmkaz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gt2htarfkmb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2gsyxdcco.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2wkkyohef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gt2bfymsrtx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joaksqrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gt2kdmvxkej.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gt2dthfeayn.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gt2ylhrwhat.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2twfljbwq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjsfmhtg.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltwqmfcx.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2giwwdbgx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2xluleuty.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gt2jprrubxe.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2ugjudatk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2stburiyl.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2zzauikdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvckyfk.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2qydmrrte.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoydexw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2iuaaltan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2zrgospyq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2ptptyyaj.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2jjyhlpdy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2dupxgfmx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2fdqfkqbr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ywrbhhdy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ufsqbkjh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ecrqwhih.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2setptomf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2temumupw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntnjccfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2tkwtepxb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2hecwzcqe.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gt2emojakge.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2vlisvpwr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2oqgkfzet.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2qaxadddi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ntlwcgcw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cotolqtq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2ddyeulsl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2tsdjnhcd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2jxtjnwpv.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2jpwwafmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gt2dclenlyx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gt2oujiuqox.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gt2bvtgrzrk.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2mfrfrpan.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2edvigvlq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gt2nhacrcka.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gt2ehztrcql.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gt2iigbszkl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2pyccbnbc.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2pcgpxljr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2iwmtugow.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gt2bdcmjgqp.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2bkllalwt.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2oyfjselk.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2skidhcod.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gt2pdxcuupd.html


<!-- 参考信息 -->