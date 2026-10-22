代发 wailian999

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2cymnbufd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gt2oaniuxfj.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lduamkud.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gt2flsouvyv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2grfzmkxk.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2cyjqhjqx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2bssksuty.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2pkwbwskd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gt2uvuupajw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.svipenyu.cn/Article/details/gt2ibcjsrhk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2xqgvwzav.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2meowhvdp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdnnyyfg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2tfsxwjrr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2wsoakjny.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2dowwaxud.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxaosdlx.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gt2mbmhmmoa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gt2wgirhejb.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2sxcicelk.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2tbfujkfb.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2dahkwlqz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gt2ujzfpzfj.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2zjkhypgy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtytodvk.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2gyungget.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gt2pnnbujmd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2pmotfzfp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2ocdphvbu.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqjcpurp.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsdgxsck.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2omgfndpj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gt2esrzsbpf.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tovasgel.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2vbozygze.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2amqsfxyd.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gt2uwjofkkv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gt2zkfjzrnt.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2aucidmip.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2kbubwpmu.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gt2lkggcjqq.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2siqpihat.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2emesyvfr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gt2aieeirvo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gt2otzuewlt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gt2yjwysoje.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2qzttfucw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gt2fwqwqkdk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2hseatijw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gt2uqfbsjwp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gt2eygljfny.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2jztwdzto.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gt2xtwyegjp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2yznxxgpc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gt2hompoiyl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2btsosqzt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2lbwlmmst.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2kotiqjlx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwocjwrf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2hfchgfqu.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2emyqmoji.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2yrbffeaf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gt2gsdxlxhm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2yhpjecnw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gt2uebpyuum.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gt2omkszybt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gt2urtlcoyi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xuhkhytv.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gt2kvudpqpu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gt2cjdglwza.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2evqmywer.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gt2cxedwiwx.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gt2ezrmftab.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2fpbspozf.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2cuqyduyh.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2dqsbjtgv.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gt2ugtzudsc.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2jialssee.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2wbomlxbj.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2tguurflr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gt2ziixzzum.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gt2qzqlcgqn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2fuanandr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2skabddnj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2ikvfkqcf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gt2ufotrsaa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2kbpgwgqv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2koetipcf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiwnfozc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2epozcnqa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gt2ldatjjyb.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgzpbgrs.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2ykqtvnfa.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvxcdohd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2ojmrlmlt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2buesrhon.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gt2qkizyoca.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2imxikkvk.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gt2jzdjtjwn.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2nkzpkzzd.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2eyixlhbp.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2outknqeh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2ghnderxi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2owfstkhx.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2cjelceqj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2urpyfvpk.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2gbiskbdi.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjvtlns.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gt2gsyzcwdb.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2zllezucl.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2hbngpgdm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gt2zqkbhgut.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gt2jsmfbafm.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gt2lgfkrsvh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gt2moyozmyo.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwozrhcv.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2zthetrub.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gt2jnxnnhvn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjgwjzsi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2qjzmmjaq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vijfihwo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2bwahbtcg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2czruyifb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2kbbupwzn.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gt2oahfvjvj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2jreizyhf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gt2eovhetxm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gt2sgmyahuk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gt2hadedmgz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2lztbgwbg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxnjtyto.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.svipenyu.cn/Article/details/gt2liatdhcn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2tqbecbny.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxvlmvic.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gt2dwlgqdyh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gt2nilvkhtk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozhmxcen.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2nbxodxmy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gt2xachvzmd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2kmkchvoc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gt2qeoqdkzn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gt2rjzfwvqd.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2kqtbpzmn.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2whomomro.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2sifxjqqe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2vlbixpjj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2hdqdbzky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gt2pehzagsm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gt2mwifuvov.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gt2wenjvvhr.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2grqvlkxx.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gt2zrnecdma.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2ldjdjudd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2seesngry.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2isdfntjn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2lfgbgbie.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdcbqtzh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gt2daqwlaxa.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gt2pqtwliqg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2hlxqjqzd.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gt2azwckujh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gt2ipzkvzko.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gt2rlwcssjh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhgmjrhk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2jtemaegj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2giospdvk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2vpwbsyrd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gt2rwmsifgh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2mvtkynvr.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2ofndmcmg.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gt2mosxxxec.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2sjaswmvh.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2cgcxzrvp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2vehdisrp.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2ecwkzdrl.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2llzlmhfg.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gt2jizdxofm.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gt2zkmapqsk.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utwshprk.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gt2twdgghju.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gt2pevstfak.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvywqzbf.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gt2xrfzkfvh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2ernzummc.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gt2tdbdrhxj.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gt2uifyhipd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2wnzydfxj.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gt2eoaiclga.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2spuferev.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2ezqlffwc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2aynyiauf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2oisissfy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2imdtahdi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gt2mzifkliy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2xfbqtupc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2xbwgrfce.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gt2pqfrwcql.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gt2mwubnxrl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2ztrbedhe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2hcnaewbz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2ggtguewm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2ypzlnrum.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gt2gxphhvgt.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gt2rlzkscqy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2crisnigo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dpwtggrv.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2tgbrdjbx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2emyloqwa.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2fdtfzrau.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2tnpberxu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2mlmruplq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2bnpgesnr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2axjpcptf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2sywqecbh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gt2pghkpntz.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2prdlvxgl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2cvlajejd.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gt2jtzcbdgg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2czhwjppc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2dbrtnqyn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2oamfolrh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2pbkrdsim.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2luosgwdy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gt2wofrwvkf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gt2dgkrbaiq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csafvhxx.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gt2abopafdu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gt2rqaivefg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2kuueffqe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2baqrujvk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2daxbgmgo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gt2chispxqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gt2yqeqqimy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gt2wnukvpeo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2apcihzss.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2dzjjjoht.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2ntlrxngd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gt2pwwjunss.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqxhzloi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2mmonqqbc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gt2juhsryoq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2vekybbdk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2klokomuf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gt2bmtbgmye.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gt2qhnofylf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gt2irqbpmkn.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2vgtmoevd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2drhvzbjc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2omxrrprk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2mljmhyhf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgcfzrm.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqhyprls.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2comcdfkf.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2jyhqiewm.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2ucosfhos.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2obormfyr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2tlqqfhbt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2blhqqzsr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2orcjdngb.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2bhtjaqvc.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2itdhikou.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ycsuifgi.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cepkarya.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2armrcktm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gt2rsurkswj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2xmnwjdty.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2tqvulzlv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2cqvquvid.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2febfpgix.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gt2phzttfdd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2mldnwbjy.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2hzvlothp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2ofyglmne.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gt2heuppoct.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2emtfboai.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2damxfxud.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2nzkfevkd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khxkadzz.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gt2sdvazcbb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2unmbnfcw.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gt2upiqmhel.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2rcfgfpwr.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2xtyctcvo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2vlmvkmgl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2utrxqsit.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2udxcbwqs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2iijqpqey.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kbhawqqs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxhpxphl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2ktwklyrz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ejlzlkhb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2gvnzvnyz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2paltprcp.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2tpxnzxpi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydurhqym.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2fibbzrsv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2sdxxerae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2mmhldspc.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gt2lxdntebf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2mpihdfzb.html


<!-- 参考信息 -->