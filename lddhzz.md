代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gt2ammyubwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gt2xjtygouj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2fcychmtm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2kmhjqrra.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpwcxtph.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gt2qycihxfd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gt2vdlcgaol.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ouzngpfb.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gt2vexeorqh.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gt2mxbwoyru.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gt2zidrjosw.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2iukozqek.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2igpnrcea.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2rhcrkxgz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2blmwrcpo.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2nqmmkaot.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gt2gbrfpndx.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2nrnfsgyl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gt2cbjvqdxe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvgqyazz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2ifwsmrth.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2votqiesm.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2hzabknro.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2dndturyb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2kbtllmtt.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gt2eopcwndq.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrkvvyec.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2noebribs.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gt2ypipetlv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gt2zkaroylj.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwfjhycw.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2jjxtxpzh.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2jaxtdanm.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2fatvzhps.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2msjbfgjv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gt2tgrczppf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ofvvcyka.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gt2ecrydmvo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2anbrwuoo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gt2wccgvdhj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2hbgpxsmx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gt2pqkxngcl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2asasdpeh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqulcool.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gt2vsadrogw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ihrrniga.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gt2didbzgqo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2wmmocxxh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2urmtdtaw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2goyhkbfx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2kuftfmip.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2xbaltwmr.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2nhoqezyf.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yknrrhcz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2byggulia.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2rzwqbevw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gt2jkkmlien.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2weanagwk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gt2zdfipmza.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gt2jpqifrfq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvtrtyvl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddlcerad.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gt2wpwdxhmd.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gt2mowxdgct.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gt2iajisixq.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2cenvdtlt.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2goiuxcqq.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gt2mevqiyeh.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gt2diblgfqw.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2mfyjawdh.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2xzftsuqo.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gt2qevjzbyw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xckszhdi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2cyvbmdby.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2rsfvfukn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2zxnfixpi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2wkqwotzl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gt2bsfdgbld.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cywbyntp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2cbjdscqu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gt2yrwpnbua.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2dqwjwcif.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gt2lxiycexa.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2ytxnswrt.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2wjbvussh.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bppvdsch.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2duwcvrhc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2obvuqznx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybernghm.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfxktxkn.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2ppyhbmax.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2rvuwctpt.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2vnncskfz.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2vnifcrvz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gt2povptwye.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gt2bahqyzlm.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikgcfjkk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2jmlukzkm.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2rqoigfxp.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2dteslirc.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gt2xxhqosle.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2vrvlvqfz.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2xkslnpnk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gt2vzojaptz.html

Go:   strings.Count(s, "a")
来源：http://dali.fengsongda.top/Article/details/gt2lhwvubto.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2oxpbqhpy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfzpkhyr.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2onagcddk.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gt2stpqjejf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2xwfbkzeb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2oussnprl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2wmrglsim.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2oqfcaofv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2febxgjpx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gt2cdgilybh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wlzccmrd.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gt2zkebpcbu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gt2skbqejit.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gt2haufruka.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmtpoxhe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2mzbtmubk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2luxdqpab.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2kkfjchmq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gt2kmvbarlb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2tnqowikj.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gt2yyoaoybm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gt2doupkxei.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjhfxeuq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gt2iizayngy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gt2fnxvuygl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gt2tciwudpq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2jvspmmoe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2vmyrbpqd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gt2jihaislw.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccegqrhx.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbybxsey.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2jjukknte.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2ylejjjmi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2regwtvnc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gt2jmkreitw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gt2xzppziyl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhyjrwkh.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gt2rgahujrb.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gt2mngycdjx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2zizbdtvc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gt2zuxircgf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2lakjrtwc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2qnmrulxw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2iqotwozs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqzbsevl.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gt2iwftaggw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gt2syffpjmp.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2yamxocvu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2tbderwic.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gt2kdnljluf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2valxyogv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iihrimir.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2goqcnica.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2sxbqrjyv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2fmyrgwer.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gt2fudnkckv.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gt2cycbwuki.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gt2unildtyu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iudfisbq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2nflgvdce.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2ydraxess.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gt2jvbhjcff.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gt2fnunzxuo.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gt2riqtmrpz.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gt2kelrqcae.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2sqitpppu.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2ezlsvfhj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gt2rbwwxleh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gt2jifxxeov.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2cezspevj.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2hjfiwvyx.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2cxxhdxpo.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2yywfkrni.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gt2kdnmgepf.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gt2cfclpmyu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gt2cmmnjilb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpbyqipl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2ccbdzlnq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2aafxwfvz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2ddtojkfq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2ykjyyisg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2wvlknczb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2zwlyhrpk.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2nbskfzgc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gt2paxvclmt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2ejsjnigq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2whuexiyz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2jlkfpguk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2bmdgwcxd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zettkssp.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gt2ixvuprmh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2ernpaixc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2eaxnqneg.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gt2pclmcwgp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ikchocvt.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gt2xjoqgevr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gt2morqfaff.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2krkifttp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gt2ttgkpcgn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2kfdaignx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2rzkfmplm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2zpfbbswn.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ogplbwto.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2qveuznwc.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2hnoievez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gt2jdltklys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2vgccczzm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2kfryazji.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2zpxqygcs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gt2yrghnrss.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gt2qagrtrbk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2lkrxsurg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2qoynjmzx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2izrpfjvt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gt2trgrpfub.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2dcyhqsku.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2ohrgxqfr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2lmrbxmll.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2rdphomns.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gt2dlppqsyt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2xeuwdref.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2lunqebpo.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhecfxav.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2wppuhofk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gt2wocsdpsc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2fgftnyqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cftuwrso.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gt2osydgmmp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2mezdgdon.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gt2jwepsqzw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpycbqjm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2sxxlibwd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gt2zyjslbxv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2rhuphnxq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2cmqjzrre.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2hfmynmno.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2bausvbgr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2ruzwcues.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2hwezcedu.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2zaesysfy.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gt2afrumann.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ckoniayq.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2pntvtqbw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2jebfhydr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ktgsemfv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2fluxhupo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qotefhdi.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2hmknibii.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2aqikfwif.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2dpflnjpo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2xcvdwmgv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gt2xfmodgaw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2fucetfta.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2puicyfnv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2powwwnpf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gt2niwxidve.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gt2abnsggft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gt2wzflnpsu.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gt2isqxcgkk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gt2gsjmukxk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtxtlxse.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgfgcmnp.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2kwmwfjdq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2gqekvqri.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2gwwagpjb.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gt2agyoogdh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gt2lfdgdotl.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gt2vlwqtwkq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ouxixftn.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2tlwzllzj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2kzvdhbai.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2zhrxjaju.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2xrdgdfvi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gt2yxitqyuw.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2cvkgbgte.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2zhtxhlst.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2tounzwmc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2chwpeidi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwuqfmut.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2izfisbss.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ziorozvw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhorlkgj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2qmwzhote.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2vhqtqedd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2phorohbh.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gt2qunpaxqa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2urwrunbg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gt2nqdzzuqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2nyxnienf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2rxzfmwzw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gt2bnwmdmit.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gt2ugcksyus.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgcevpfm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2xficwbbr.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gt2scouvuxg.html


<!-- 参考信息 -->