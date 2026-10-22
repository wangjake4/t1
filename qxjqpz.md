代发 wailian999

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthcugqecz.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtkmuszpaz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdupvtsgc.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtqbepvlkm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtlzzdhymp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtyrbgefbl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtyjcucuiv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtrswccavt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtcecqxbdl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtjkkxqieq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtzeoyqzqk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtyolbqtyt.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtowvjxkka.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtyrhifghc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gthlchckdv.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtvdmmmbwd.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtmqmazkbn.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gthbzplytw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtbutzddnh.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtmnlbozpz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtwvbvmpwd.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtxmgzaekc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gtbjdvkybx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkkzxwsx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwwibufq.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtatwrqyxr.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gteplbcyde.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtllmjelnz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdsmdwui.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtjfxnkrmw.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtepzmrumq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtydsxmmfr.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gteczvfnld.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gtflvxygby.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtwlcggadw.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtnjdoepym.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gtgehzviuz.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszpsnipj.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtoezskaho.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtvrbswstk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gttkrebnse.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gtapulfdtl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtppknhpuv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtrpdeahay.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtuhlhznfy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtdggckdds.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtsovdemuh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtjeetlxov.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtifboaatq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjfenhsh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtrdcaknaa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtsuwqibal.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxnehtun.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gteyaskrwv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gttfvjheky.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtighpgawr.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtysgluuwe.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gtybbedkgb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gteswfwttc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqljwgvbx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiihhdjq.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtcikhcvql.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gtavgkrbec.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtrbybnqyw.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtxigfczki.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtrqyshbbs.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtbjtcwpni.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtbexyvdlp.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtqasypknp.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtqdphruaw.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtyfhizolv.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtkykjvwcy.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gthncgkzwk.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtczxavrsj.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtcconisel.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtnpxkjrsj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gttockylfm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gtojfazqgu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtmxiekfgs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gthzzpdzkm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtiiqqgjjd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtroxjhyzg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtxxbkimuc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtqwbeokjz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtwsfrdvxi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtfvumhduj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtboijgcqk.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtplbdslzd.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gthergvrbv.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsglofgxn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtkfmynexp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtlpernpqn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtalraduzh.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtvamsryzu.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtqezzozfu.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzawocld.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtetfxgjxn.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcybwxrxc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtkkrstenx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gthfwpjshx.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtstdakwoo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gttmreupdq.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtoqmukvyt.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gtevhmilnd.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtmdalaksn.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtyxxbflul.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtsrbiknly.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gttkrwxjjc.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtapemkgiu.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfrgriea.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtloomfmgv.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtntebkvdo.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gticpoqwum.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtfcvmcwcu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtqmvbajnc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtdamcieva.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtdsscfsyh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtkqnkuusf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtmgjpmzwd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmtxzznw.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gteaaktwwr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtbkcedlba.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gtcmairorm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtapvorirs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtisycbrfy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gthsrnenhd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtocndeiqw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtvlpekgxe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtdqjkufja.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtrkfnqrzk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjbkkyrcf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtfocsoirg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuiuoyequ.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtfvirzhjr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtobpyjjgf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gttkuxupke.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gtcklgprnf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtnhgvinxm.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtefwiofdm.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtdnajexsj.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtgidshtae.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gttmtnpmsc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtarsajzge.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtpdxnbjcd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtlpaisalh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtkkgmxrhc.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpnhohlm.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtrjfqkspr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgudfxyna.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtfszwvqir.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtqlnofnyr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtovylqrve.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gthhajubfr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhrbmjik.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtmarpahuy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtfqhrerxn.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtervqqdou.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtehjlnnfh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtoooaffqa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqxbaiql.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtmrbknsqu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtllwgnewc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugoaeqhf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gtrbbdccyk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtyhpcczxn.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtnuanodlx.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gthutrdbid.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gtpdnepoae.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtrexzvwwm.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtienwmhob.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtojsoiehn.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcziqhlv.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtrbvzsfiy.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtvbhkofis.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gtrbszceme.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gtzwpntewr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gtrdkhlieo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtyhmapjny.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtutwmsfpx.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtzseqhcue.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gtfqjrmtrl.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtfafhxqxk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtyhgbkpak.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtgvddsgga.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtrvtgwqqe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtafhbzvls.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjoxhbow.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxowlxbh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gttssvqpaq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtvcxripet.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtxutsuteh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtgatrdjku.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtqrxgkkvc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtrhfjefcr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtthyjlobm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtqpbxvske.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtiajrkzaj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtvavhkgyf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtpzdxlnwx.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtkdglhudg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtqnmtfcud.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdjqwrsyn.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtvluuodqj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqxbgllxb.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtgusspbua.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtpwlraxsq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtmtzvzwtb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtrdqzzcom.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtwnjwaozy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtdtcellnv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtzpkdepam.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrljmcpas.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszpwbjvb.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gtlzznuwhx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtcizewvut.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtbtauukbb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzjsbllcp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbtlnqgpl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtvnqmhivc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtwgcnytee.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtgsuhjuee.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtyzmvwlqb.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtfwtfytay.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtpznsbtdm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtixtzisko.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtwgzjcsoz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtcucuvhzr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlahxyqkw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtipenmvgl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtchzvjgdz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtutffhddx.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtokrxayjl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtaisbjagj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtzbvhyzuj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtfbholeyc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtyinsaqxl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtcqvdvemg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtcgfzlkoj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gtlqqqihdh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkeeirch.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtuoprqlxe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtgkbanwue.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtragheoiz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtbkxppgsp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtsrgnudqe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtlpemjdog.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlowijvba.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtlkhltvwd.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtyoqiprby.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gthnnwazai.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtauevevrv.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtdnffabky.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtlvnevcrm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gttkpltcen.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtvejfxzuy.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniqyrdbc.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gteizbfnav.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtvwcrrurq.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtgticfaoc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtobyxoydc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtdgfzcdbq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtbbyfhuzx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtyonqswyf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtwgfprsna.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtmmakhzme.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtxvvzlvbp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtqwkspqut.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtzbjoozfl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdszlaapn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtcojfigcq.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtzrnvrslw.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtzehjzxqw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtuybkqjru.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtibzguixs.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtocpmtoum.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtnuslpola.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtbamoqeur.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrfewhyht.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtfggylely.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtiojvgigr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtkjjvabfd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gttdykezlk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtcktgbvlu.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtspctixgn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtxgncztbc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqntkokab.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtsbrlzxzp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtyqoghost.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqhtfvvoy.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdibfcca.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtvjaanbjh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtiwhmktuv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmwvwgygy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzlcvkdby.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gtyncrwnpt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttsbehqgr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtnhwqegim.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtmkfyzdvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmtrjszqp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtblsjexau.html


<!-- 参考信息 -->