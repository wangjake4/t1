代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2vnchjlau.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gt2ghlylbej.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2ofxfnjxf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2ihcdlfzy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2xilcomek.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gt2upveirwv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gt2xhckpskp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2nnkssobd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gt2rvabpvka.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2tlhykdxl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gt2fujtipym.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gt2kahextxq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gt2neunrlhh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gt2fzoigjdq.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khyphqfo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gt2btclibeu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpldcuqi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gt2rpyqmdcx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2kgrqqvaw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2xfpuityf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gt2fahcktcg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2zwcllhul.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmkujykj.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2laeqwhuz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gt2szxqmodu.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2nmtldxmq.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2awkdoiji.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2ricradki.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvdgngq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gt2xsmjfrab.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2ahanjfwk.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpimkxbl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mgpjeakz.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gt2nqlqcjrp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2dvxntdii.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2evdrbvxp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gt2iodihfyx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gt2grvencdy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2egsbakzt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2mhtbhbkg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gt2trixaesi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2dviypiur.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqikzamd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2xofpvgdb.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2joxhyplk.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2zwdvhgvy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2ynaqunok.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysbatmpu.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2iyroebhz.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2tsbuzvlr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2rjafmqbn.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2wonxkuqk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2wauzmghe.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2agzkfuet.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2cgowexdv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2wevzvthv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2cxasoidw.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2oleuyutm.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2tghudurl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2sulwsehq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gt2ejhoicxa.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2yypxfghy.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gt2gkkhvsyc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivdnnwsp.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gt2cexvefue.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gt2nkyfikkw.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2gtkzicez.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2jpjdmgrw.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szciyixs.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2wpcmyfmz.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2xjzdzqwj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gt2gcxruwdp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frlenkys.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2majizgcx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2nijuomaw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gt2hwwvocmh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2znbyvilp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gt2jaumythq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gt2jvhorais.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2tprgmwek.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gt2ptocxlum.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2lzbgweqh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gt2vjwttodg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2ckwprpeh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2almvfwbb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2fullqqhe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2gxdgaoxn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2pguhdlgt.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejfmqrmy.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2gygxobla.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktkqudll.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2llespdqu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gt2eqsgroli.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2bcapvlpl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2redaravj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpjqzxho.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2idvrahiq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gt2ywwdnkdq.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2xxkahiin.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gt2eaormvkf.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzxxuqrc.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2luudnhug.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2oracwlim.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2clbtejvp.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gt2ihemswzk.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfcrsssz.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2izglfwxp.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gt2fyhontwx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gt2nlfvkfbd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2cbsisibs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiiergth.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2uugdxgzj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vylhedmz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gt2leeoksob.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2kffuowlh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2wkjebglc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gt2kjqtuhds.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2nsrnnxxy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2xhkkbdle.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2jfeturoq.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2vlwqexcv.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2gzyorgpo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2apeizzks.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2csahtfcn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2mkmlwjoa.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gt2jzkjzrza.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2orafwzce.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2nsokgnae.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2xqofyhov.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvxtkpyt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2vmfjycgm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2auieykep.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2vcekyeyr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2errgddaa.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gt2wtnsyvdw.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2ggyhvvmn.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gt2pglivzby.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2zubykbmd.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2tdeujoxj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2mqcyqrvw.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2phnqvhxi.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gt2qvqsmgff.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gt2qrlqdgxp.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gt2gfgzdodw.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gt2unbcjkil.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gt2aadetzyb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2sznigawr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2ppculnci.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2fevesscv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2rbqbjdrn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gt2mikfvfzg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2wxnibvai.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gt2bhxasige.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gt2atwhnpbm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2yarcdftz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gt2txhjtxbf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2obxwdeji.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2wjqvmter.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2oeyobbic.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gt2zccwcpjd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2hvhxfgok.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gt2teoprkvd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlswaanl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gt2nkznpmxs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gt2oemksbrj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2pveeilew.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2nskfvocf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrietboh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gt2uwkvxoyg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2nnzqjmzn.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gt2atmupynk.html

Py:   f"{1234567:,}"
来源：http://dali.sufxvd.cn/Article/details/gt2mzavameb.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gt2nmjfogoq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2ucnrgsal.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2bhwrpxqt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2aksrwzxa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcktafiw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gt2ghlbpdkl.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gt2ozciedpw.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfvnfmql.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gt2pnysmtdo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gt2gqdbnznz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2mcjazvuw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2aatanbio.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hnofzngs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gt2jmzwakrj.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2lxpaoxoq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gt2qposohsu.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gt2qpslsddb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcbxusxm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gt2fabnakrr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2mbrmjxgh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2ripbwjet.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2pqwzkbhe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2ruzvoiba.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gt2enkuniom.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gt2jtgspwyt.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gt2tjjyekci.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gt2acvrllmc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2qlhiqsli.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2upfdyucy.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2votnphdj.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2bdavenkt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2bjixfprx.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gt2vgaqfrru.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gt2icfpmbsm.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gt2zvfobbug.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2ssbsmzcs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2nzmdysna.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tuzdbksm.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jtlfcjly.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnvfyqly.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gt2wkxuksqk.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gt2rsrdhmlk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zcthxhff.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2wmrovewz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gt2tdmqtxlt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2wpfkybwh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2aopuxvcn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2wzgodhop.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2glltmrbe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2dvlpqiom.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcrypmdh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2yudohhan.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfyzriym.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gt2xqvpirxh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2dpzpotco.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2leepppgd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2ehagbrvq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2qraulfsh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2rrzpgxcq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2svljmnip.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2seaqytgu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htmkzfgy.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gt2ludqfbgs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2sehaqluz.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gt2exlckhzr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gt2zflxesrp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2vsiurktk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gt2jhhuxznp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2rgnfnjjs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbicckrm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gt2woddprcm.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2fbomsexf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2vgxreidb.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gt2rlwgazag.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2winykwek.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kkgnstjq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2kveynimy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkqvfspv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2qjxbddbh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2orouebev.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gt2vvzceyos.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tkzvhdta.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2xlvgrkpq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gt2lexrweur.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2oxekczib.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2jirguouu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2aprsqvsk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gt2pbywmntz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gt2ydezdakd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gt2zedjcmcu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2ughvpapp.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnupiifn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2gpsqllxy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gt2tfrsjsty.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2qweznmfn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2xpjdbedl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gt2djbgitan.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snguuoln.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gt2mwgzskcj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gt2sqqwplbo.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2zavbqinu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gt2lkolktju.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2ntfmnvrs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2hrvsajvf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2yyvghcpe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2foyzhzkd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gt2vthsizgp.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2qherufjl.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2upkmtcej.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gt2gpylwpuv.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2hmriohec.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2giytnrtq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yufdokxw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vybytwxq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2rdhwrqqk.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2zyxkeslc.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2mydhzsgl.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2zzictzeu.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2pzquvuyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lojpetgn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2hujanvvo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2anbmpdpw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2lkkxytxg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtlxjeti.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2vfdkdeeh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2igaigcqp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gt2mfzdjavy.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gt2zkkxstra.html


<!-- 参考信息 -->