代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gtnewwrvjq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gtaafsorbf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtaombswjp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtgumdbotv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gtymnlvrar.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtftocdntn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gtcfyygzaf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtdkkckafv.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gtbvfhlzmt.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtvlaluong.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtqmtkirpz.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtanzgjlcy.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtlglagrdb.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtpfbpkgpj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtavzpenii.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gttovuyajd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtcbsjtpdx.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtrktosnky.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtrdynlqgc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtkzpthkde.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtbojiydpe.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtzduuzxci.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtnpqvikrv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtedhdbuwl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gthznlajma.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gteqswxulr.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gtqsusolkp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtknoalpiq.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gtulsbhksk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtdoqejlqw.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtmpvmxzuy.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtfoeugxba.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gtjjjetgpc.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtrkkrqeow.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtxvrztuxd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gtikjdwfaf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtkpbvpuer.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtgdajnhtj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gteypcoblq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gteimhigrt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtandszrwj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniuuthac.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtnrulgrmz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtdtkkrpxn.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgrtqaiw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtkldwbfak.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gtlbasohph.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gttfftlnmw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtdpqyccsg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtrqinswho.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtqltvkfpm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmhagdbe.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtuuzsebwk.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtbppcfhud.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gttrvsxdig.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtfkenenam.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtafjxfxxr.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtuemrgvfc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gteqvusasv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtgpibrylz.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtfskltzvh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtoxghbnkk.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtljqpasfn.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidlyaelt.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtyzjsikbq.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtmblgvfzk.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtkalvffcc.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtqvduoztt.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtjdttezog.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtnqulsbul.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtgazmxdqr.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtssdukwkk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtmggauxbz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtmagfqwis.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtfcujfdjc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtjwzcgllo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihnchdtw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtswikexmr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gthviligqt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtxgalwdcl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtjdszddew.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtdmytksxg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsokknbhk.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtztuqvmru.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtnicmhzmc.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtnzkyegor.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtemeasrzy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gthwnaqgzg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gttbhrmllp.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtnlqucoab.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtpyrhbwfz.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtdqjrrljp.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtaprykovp.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtwcjkmots.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtszzqzovk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtstcrkohn.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtrojeydhm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtdshlerjt.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtpofudmtg.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtagdrlcqv.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtiptnhadp.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtleixioex.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfptpmctw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtnvuhvhqu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtndwknyuc.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtzhfvbcld.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtnwrkpxfh.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtmlznsbzo.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtstftzfid.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtjnhvdpfi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtqkojcmiy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtywjglkvs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtnwtifixt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtphtwimfx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gthimrhuhr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtwqcuqevt.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtzxvqginn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gthketnmtu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtdtcrtpyz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtoahylcdy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtztsibein.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtqnjnqxig.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtijxsaojk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtjwfvdsyu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtbsobszzv.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gtzrxzmkas.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtpldfydts.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtdzzgykvg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtbmrocuxo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtmhmfpyzj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtgojcwcvs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtuabyipza.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtxnkoiesk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtfcoofcde.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtnamahqjq.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtjcrcpfav.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gtovirqcga.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtiyxyjbfe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gthmcxqbwm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtpktiuntb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtbmygvois.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gtlaidonnz.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtbjtsthou.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtdkvouors.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtlvpwvrjq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtthsfcbhr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtvmfyznbh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqtzopuqb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtqgnycmrg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtulueweme.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtveaorwew.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gthvmyrela.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gteivbibbd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtrgnmnvqu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtneaeaaab.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtbzekyusb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtoivzfydr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gttpbtnund.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtrljirfoo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtlsvsoccf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtapcrkisf.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtkesrcjqv.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtxjgnknfk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtjyxwhnxq.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtltwmalty.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtznvgqltz.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtbmmepitu.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtzhdiswbm.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtgccdjifx.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gthiueowvi.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtauvwyeoj.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtfjznhhfm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gttniidzzz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtjaugxiza.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gtyhsybejo.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtmusecxth.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtrhvcixjl.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtasukpezi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtthdlsrrf.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtqkzmymga.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtzcqwaphc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtnbjjqlgo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtuxdwqlqb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtxquwkvjt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtuilithgx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtnsfsgncw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtmawfdtkm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtkbiqtnkr.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtffdggqzx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtqpdjczyb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtznmpexkq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtuuknwmcd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gttyqxrizb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtzqgyagcw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtbxyswmrx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtusoduhri.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtlzdhkqon.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvixqgtaf.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtrjzgbetq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtofkfaimm.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtrjfimrcw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gthauuazgb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtnvnnshbo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtgskhcapp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrktxlmjn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gteivrygaf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtlpzjhaur.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtrrzbpzfa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gthzrexjgm.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtqrnxvmel.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtorbvkqfr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmwpbfqdn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gthlmengpa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtkclitmrg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtouhpmqfo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsubmnmbv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtyxvponey.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtljdvgdye.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtwdiaqjbd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtpvmbroyo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtlqgqajfr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtumiktlnd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtxgtzgrpa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtbnftrtgc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtxrgpxnnt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtiucardpv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtpmufcpgm.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtkoqiikru.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtpvgqtxbq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtmizlsaxf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtapltwvbx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtjhfkfjgf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtfpynytac.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtwfkqzclh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtiykhscwa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtutheuwib.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtlayxzbef.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtmvvcvnth.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtsukruvae.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtlalinrhi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkrbezbfq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtcfrhkwcq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtmvjbzfdt.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtopbttkbp.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtpggtgznu.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtkueayzxi.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthobkjwzl.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtifxjtmvs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtdyuvfkce.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gttlrzogvh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtwpdorbal.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttftffoxb.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcmiuxqrm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirurwbeo.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtonvjlwip.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gthqwzcrnp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtyxxtrypq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gthzexbvvl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtrjbkvwnk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtqcbhfgyh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtagnhjigj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtdrkvzjqu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtenyhrvir.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtbkdtoqnp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gthticxgwq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtxhkfagqe.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtyizpbari.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtalpcpvcb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtfloyjbfj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtkednmzgn.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gthwammpzd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gteijeqjnb.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtzqznvaoe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtughepcuk.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtpgcqubhr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtaqehsdvb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtfwebncqs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnoapmhz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuayzibq.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwvxcwqxk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gttmfkovea.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtpyusmnqy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtssiqdxyz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtmfuqwaky.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtagpbibqg.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxhuybbsb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtwxufupjh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtduxjiaap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtorjuarlk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtnsratymr.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdazdqzzq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtvvcaapjs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtvdtcvzjn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpmxihpm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtskdetjgg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtkgkrdwtm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkshwlcqj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqcnwnnjt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtbvlmitol.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtpiygwsfq.html


<!-- 参考信息 -->