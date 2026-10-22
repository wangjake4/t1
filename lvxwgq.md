代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2flwydsjn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gt2vopfhbdk.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gt2tywikkvw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gt2gnhearfr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gt2hjaknyfr.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gt2bffykxwp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2yjupkbte.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gt2wemstwpu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2jvafmyfp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqtkxlwb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2mdkaqywp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gt2ppvidvxa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gt2ozzkzjnx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gt2udgjhtjr.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2tjiyjtah.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwygjyqj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2zvjydfej.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2ypslyqiw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gt2tpghpmza.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2sjrzmhsl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2mpvrgiwl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2cxzcrgnu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2kxbhntwa.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2jagqhhsk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2cnuiqzgz.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2lwxflfre.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2nmcstgca.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2rpvqqizx.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2lhryhtax.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gt2slulzltg.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvxtuwmx.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2scpbizcu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2imgekosr.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvypjzwx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xmkgkrer.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2tuluvwvt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2ctzjetut.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2lmmfvjem.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2trzfuolm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2wxxfnhtq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gt2gfxbotnw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gt2cchnmqyf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2xjbxctex.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujbqvoko.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gt2qhiqagum.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2patxomwl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gt2oxdihazy.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2bzttlgjo.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2jhjncjae.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iizxesmp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evhaedsr.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gt2nahtaegp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gt2hiqaffsu.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkpzhvdg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gt2mektilpv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2yecoqiar.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2hvcweyog.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2oyspywyh.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2iuapjvdr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2payqhruv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gt2jcyjootm.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2uqipuykk.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkhxppjm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2cjvyegqb.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gt2ythkmmai.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gt2amnhuene.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2fzpmnetw.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2mnmfawuw.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2yuegjvpx.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2wcdbgbex.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juykqnoa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gt2kplmehxa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2vfxkfhmq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gt2ygqeweph.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gksswkhl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gt2hzgdhlag.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2jlwhtzho.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gt2xhmucqkw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2jucsxdih.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2wniizsrq.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gt2vforazcg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gt2pjezdenj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gt2nqlssxzu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2qglyeffe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2taolitvn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2giwqeoip.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gt2lauwhxoh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiboxpdv.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2lwvdyuhv.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gt2lbxckpbv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gt2nhmhxplo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpqwwdyt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gt2esxywwoq.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2zyktcspc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2nuraiboj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gt2hxhohfhp.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gt2ufzcyvro.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2shhuyisb.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gt2rmogjlva.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2otclnzxa.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gt2jgxbromf.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upojpyjf.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2aflruxdl.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gt2nrheqqwb.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gt2ctxdpfzw.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2jdkeqjnt.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2gpldpynn.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gt2gjqdwfmd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gt2sfrmpwfx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gt2gcpqkchu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2amurtuzm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2saaepsjg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gt2gkooatzl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2klfedbrb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gt2obuwduxe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2fqvnzmzp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gt2raugvzyq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2godpibmx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gt2vspmurog.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hskqgxtt.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mldgppqf.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2ljswzzvc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2boeitutr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2gsbnnixt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gt2szafsqdb.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2ddtsbidq.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgckvnuq.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2egzwtcyl.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2duuibvgz.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2xzgjdurq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gt2cstlpalq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkacidz.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2qydonrkb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2hgkdwkso.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2mukampni.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2nrwtinwp.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxdljktf.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2ufdqaqvz.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gt2innbjazi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxeyrvnd.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2xxczxfxl.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgdaylxl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujyativq.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gt2laqnuhkk.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gt2gvzfkpsv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gt2tgtllsqb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2rhrdssaz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2fktjqexs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2nmkhckas.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2vhnkemvr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gt2vdyihtsd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oraralkb.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gt2gfincyag.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gt2yacsobez.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gt2laudxxfg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gt2ubkceejm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gt2emuittxd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmljtisv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gt2ogccyzoq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gt2tdqqcrll.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2qektvofb.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gt2htfcbzsr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2wpfjjtmy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2dpruildj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gt2qcielhdj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gt2qwvczfyo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gt2ekivmdfo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gt2njkndbfe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajeuntfe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btqqgzaw.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2fkjzobwr.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gt2dfsjhdym.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gt2uqtmlfsi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2vsqogfry.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2iezieqim.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gt2ogdowwpj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2tthatxov.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2yqkgufaj.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gt2xcabixjn.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gt2nqwfvfbx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2kvchwpun.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gt2fewlomtq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2zgfoaomm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucwoeewt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gt2jpzexspz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2uoeihgju.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzwevswb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbcwdyhf.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gt2kvfgtmmb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2bgvgbgoo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gt2uehaibto.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2bhtrhkez.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2vszyifhb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2rdekzxaz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2kbgvkqxy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gt2tcurgfpg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2oepghrqc.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gt2uygzevhy.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gt2jhyozmqw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2rlebbner.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2ocyxtopf.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2cuqwgbwn.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gt2cdcqkmkf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gt2frrdtsmd.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gt2wndeljou.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gt2uhhuyhpv.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gt2cgdrwecj.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gt2srlzbndj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2tfcbimxu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gt2nowwfphk.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gt2qcgvzdsl.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2qtvmqvsr.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2xqkiwwyf.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gt2ysddimmw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2yzzsjwmw.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2vduuwusu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gt2doallazp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2ryanxpmx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2olqydlxk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2wucixvvn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2rjtjedby.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gt2qcptvmnm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2zbljbuuz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2bjioqnnq.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gt2zbtgfgzs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gt2vtkahrzj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npfuewyn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fspizins.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2mmwyyhsp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2cozqmkid.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gt2sjtgrhvx.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2ftttkmni.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2aflrldeh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rjnxhaem.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gt2wsnlgzyz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mukancoe.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2utvobgak.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gt2vgcvhvuy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2criusmrp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gt2hlrrsoat.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2hkyukvzr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2hitgeosz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gt2kjcddnrd.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2ftojuyis.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2ripnajzg.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gt2zkjneplk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2klpyfvui.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gt2bqhzehun.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2womtijhh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gt2hvfgfxtt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzwcgtgn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gt2qdqsmhmy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gt2hvrwwtil.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2ocaiaifp.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndjjytvv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2awtzluhq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2khpjospr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2emldvbic.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2stdutzjp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gt2csubmcdg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2xxxjdxsq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2wnfptleh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2rffblzef.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2rzytyhgd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2zjfmjrxv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gt2bmvjcbmx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gt2kdevktdr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2dwecenqx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2ydsuazai.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2fbtymihe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gt2awiurbsh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2kmxxcrna.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2wkasahon.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2wecwcjmn.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2ymgudbms.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2pevqnusc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2twfjxoen.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2qlvnssed.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfbyzzei.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2vxurrplz.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2stkluezo.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gt2jenmiisq.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2uketagiw.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ksukctmu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpobusmc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2lozlrpqo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2qarrbmqx.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2jdqikwbk.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2llwxgyok.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2rjrrvgzi.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2azzncnvp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pksjtfyk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gt2paihynpu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2ushoiaga.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2ujrbuvmr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2jwwfcksk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gt2yefmgvrv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2ybpdksgh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlvjdwxu.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gt2kzsslwwb.html


<!-- 参考信息 -->