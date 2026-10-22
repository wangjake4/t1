代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtwhwnfdet.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtsxjpssfg.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtbreriyjz.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtcprvbzyq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtnelzuipt.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtkmtesfgz.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtkwrkiucx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtgyussivm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtaylytywx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtjrkwhizi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgobckwil.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtywqzwfun.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtoyglqjcr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gteabrabls.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtnxqrvqsc.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzffdrhmc.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtwzqknfcp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtclienndk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtrfbloyri.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtjndyhhch.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtzemqfjof.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gtwgdbjbnr.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtldhpkilg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtazowgjxl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtnmptkxin.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtjzqrwwgy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtbolecpil.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtwihgnets.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtpijiokla.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtazhtqjef.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtplmzghfn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtdpkvueex.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtirapxlzx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gtvvzjwhdn.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtmlxgaiwx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtxqkizjfh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gteytdastq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtmfqgqsrm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenlongwang.top/Article/details/gtcowgshvd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtchdaeruw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtqizsfdmo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtykkrfywk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtcymqvkhs.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtcxroqqse.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtfkbluanl.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtcsafwydp.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtlvusopdx.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtswwtpjen.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtuuwmbvuq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtkthxqlsr.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtgvdaycku.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtshepujnu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbypndbkl.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gttqnmacim.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvnbptspe.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtwttbqegb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gtrryszjql.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtyznliooy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtwnfyyfle.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtxxefjhuf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtpxtuoygt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtsbowtier.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtdunoktvm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gttxlgqeah.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gttwxkaikc.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtupbqndfp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtkbinvaky.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtokuiaqch.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtnmunkeau.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtyhsiltnd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gttaixnnrk.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtdboejbru.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtnefjxoja.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjshnpww.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gtkzxpkkbl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gthlwenedc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtcykztsjn.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtvoiwanha.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlelwpqki.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtxcauwhhz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gtsdmhtprv.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtbwvzyepu.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtjhspunxd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtycpzzgtn.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtcodvzxeh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtvxjsmeot.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtasdjmjnx.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtuvkaddht.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gtdkzuuipl.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gttxwidsfe.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtwiwxkmnu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtnbnthelv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtwsylpipv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gtbvakyxex.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtwezhupxk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtkaulqnox.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtbdkvlpkk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllctjxel.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtosfeplrl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gtkporqppb.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gteyhvsjli.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthialunkm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtgbuchhaa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtxkcqgbyz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtkwtnvatq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtgkyayput.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtggsyfxic.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gthfyhpjuf.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtztaourad.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtdlkalnqh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaifjtmz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtketchmmp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtqsyyoadd.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtiihfjkqk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtknfuxvdd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtgcfugcas.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtpwbgwxau.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtzhlqhzlz.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtdelrfpjn.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtmhtfkrsz.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtbyxxdyfz.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtatayvmpj.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtgvkwjivj.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtwrlikolb.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gtjtwuhlso.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtflwusqlv.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtrgppjehp.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkalwcbf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gthfiyzcvm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gtpkmducal.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtbgscgeoc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtrguywtmf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtyouryfax.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtcgwxngkb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtyabpblzs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtddjcvhzp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gtxxgkahwx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtcigowncf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtjzdgbrqa.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gthngmfdab.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtxnwiyjwj.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtswdxblvr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtljdvwrdg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtguuoligw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtzfuioyqk.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtqwzleiso.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtxijiszup.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtczsummbl.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtfrpummrp.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtdnpagqqp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gthhdllbio.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtwijajjvc.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtbtookzre.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtjzhtssal.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtqfxdohhe.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtpgergmje.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtntbbopxp.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtjydvlrsx.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gttrjjyylm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtpaynparu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtkxhdydjm.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtgrmhctkl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtltcsdrzx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtbmbkcxvf.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtcmjabthf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtpfhzrhsz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtgjsaqciz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtpsygryxf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtuelpvweb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtairgfura.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gtuxcggaer.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtxtkjedal.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtkgbwxjng.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtvpiobjbh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtjjmeezbf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gtdxkuawxb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtvcxbxgrp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtycbzprey.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtoaeotdyd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfswjusbp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtzzqncmic.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtzotsraxz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnexetgsg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtdtgxwxoj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtqbtejwtl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gtcrludkyd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtgniojgif.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtgpciizqu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtgahqxool.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxrlcviz.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtnjealcrj.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtiaxshlqa.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gtegqslfif.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfljeegst.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gthxuwdtxd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtsnaiiiji.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gtgrtnsqnr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtdfexxmte.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gtfiuknymo.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtiabkcvuv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtsqdfyaoi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtbartvrtl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtrupquksl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtivzhcxlq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gttbmtzakd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtsiifehoz.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtivaeixhm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkecywap.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttthrjynh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gttmgwlixu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtwpkhromx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtzskezzkk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbubxotu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtswrhugok.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtshlatyrh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtmoiobcag.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtsoashizf.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gtvnpkcdgp.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gtxenmhyml.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtzulbpuae.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtzdczcsvm.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtelmwncli.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtfiecwzrg.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtzubnleaw.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gthdwzuvvt.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gteqvmpqpk.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtehgwldtv.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtvrbxhima.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtgnvqylfx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpfyoupco.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gtctuimmwz.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtwrwxtyjf.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtsfqbngll.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtezgheane.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtwzlnnpkv.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtyykicytn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtyuwlmywj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtdjcsaqyl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtbubgvkaw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtenwuertc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtisycjfia.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gthkzgzfqb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtwnwqkwcv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gthtipkwzm.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtpgkbajsz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtoxxedjji.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtaahtaaev.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtprxaclcb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtcmusekln.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtdzbjblrg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtgwpgoldz.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtzffzukpo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtecupiepd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttenagcgm.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtvoyomsmf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtixfcdfit.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtmctwwryu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtcpupeqto.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtobzezxnx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtumztbmen.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtsydouqkl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtqpibblog.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gtjgfsogmj.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvvbmslcp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtlctslrlk.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtmoktqbmd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtbbmiespg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtftkxtklv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqouhgswn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtkapumefh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtyyyivdhg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtjcxjzxtk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtqpehgmrx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtrhcfyfrg.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtolcaqtar.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gttmpxvmbn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtbkzyaabt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtfdvtphyw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtrxdrnhnl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrdfwpdh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtbwrpukrb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtliyckilq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtzmgwbpbp.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtuacyxxlh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtmvxpbpfi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gthcpizlfg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtfdpuhcxm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtgltdxlqa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtpxibvwws.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtfmnzvaqd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteawjrceb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtfkhgtumu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtxyozjbgw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsfpvfrj.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtiuhpxdzf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtchrddnbi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttgfygxmx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtlgvgvrjk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gttrgpjswk.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrwlgtyyo.html


<!-- 参考信息 -->