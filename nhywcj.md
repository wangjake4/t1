代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtivgiycqy.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtembjctve.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gteqmpedms.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtpslqrhfw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gteesirhsz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtgkhrpsnr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtejwxzjyw.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gthglliqrr.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtinkqokjr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gttupayvcm.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtsisxrqou.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtgjkiwtki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gtkiqwxryq.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtytutkngp.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtpjrkpata.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtmgbcgnpi.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtoyqwjtzg.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtfcmzbhpl.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtyvowshhy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtzoawxija.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnkldgwu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtfdwzntip.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gthniatofc.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtedyeeiwv.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtuvmbouxx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtqyupuvid.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtsugvbtpf.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtgqttfsdc.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtdwpvmqyr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtqpeqvqzh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbzuxqys.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gttcfdjpwf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtlpewaody.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtjttbpjvt.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtkrgjrvye.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtqyvwdcny.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtkvephyvl.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtumulkfhj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxihedppi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gtgmcemgzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtgylelgew.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtfieiewws.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtifmcqydj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtgtmmdidr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtmucgbwdy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtigntwuxi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtokrdpfou.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtayphlzxi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtmqkafmiu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtpehxxjib.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gtikxymhvi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gtxfnpohla.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gtbsukphhy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtgbtcxprk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gtywqtkxaq.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gtwizawlha.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtbwnwmklu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtknyywjvf.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmoqxjso.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtrseqqmpp.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtmkamlfjn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtucuidfor.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtetvibekw.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtuvwgktpw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtngyesxlz.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtfhfqqmsn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfbqqnrmz.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtvosbxqyv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztnvarvn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtvbfxesiu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtglcuguri.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtktfuprod.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gtfwntxxbe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gthhbquedn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtaifjuqrr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtkgvnecck.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtivzlodgh.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtppeklyfl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtisrgkkfy.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtforjlfma.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtrpwritef.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtlpfhplww.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtqibyobjd.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtncgmggqk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtzzdgioku.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtuykexlcx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtxsrjwcsv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gteazlktei.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtwqsbjihi.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtsfvzaldq.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtnzakqvki.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtnibfulsn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gtksedkxbo.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtkuvhadcr.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtqauzcvvi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtpmsiexdj.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtxoxtcipc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtimgvvqll.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtzxieihja.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtdtqkuvqc.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gtcqcmgvev.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtlurekpxe.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtncuqwzdm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtsptunsyl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtrcaykigx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtglsksmlo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtsghqloek.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtgzmtoejp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtrcdgpwtm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gtkftehawd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtpzkgxthf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjblbylik.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gtnabhxlkc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtvgulryps.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtvtbawblo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtovybmthy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtxomkudgb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtddlxazdg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtlcalrtcr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtfkqaasqi.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtbvexlyip.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gtjjmupxqn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtsvzqaqro.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtwbvulcya.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtnyavidnt.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gtdmqwczjr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gtxiuuzecw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtitappswk.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtbjnljjkg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gtyotxzcci.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtayokrmqa.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtcrcaprhq.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gtstwzoouw.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtfsyqyiet.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtwjsgatte.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxpzgbwq.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtsngslyql.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtpmdpgpwf.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtbbpxyu.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtdlfztamn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtbuddsdjd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtfyjtfuqe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtacxbmiox.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtdwpcaqpv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gtcrkgmllq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gteomaserp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gttlqkasyr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtspaxbqov.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gtigswltfk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gttkckaevc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtfaflcyxa.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtujsubjgo.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gttduimdzp.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtwzqrwkwn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtujxpnhxz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gttrpphmvc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtlchmjzqy.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtnkyzdixe.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbuoiapr.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtzmqvolgo.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtugqpcdch.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtbtcuyiuv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtrwauioyn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtprwtrasr.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtawsbniuq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtuzoysudc.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtcmloozwb.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtcxqocjmg.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtpkgimlzm.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmixuhqyc.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gthkbtypdu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtatfkjhsf.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtstdymoud.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtkkfdlidt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtnyjnbkyg.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtyxqiqwac.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtttcftysg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyouejwha.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtajtzomha.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtjclhklep.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtqahktojg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtomuwyugz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtotjinvae.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtzfcuagvl.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gteybsrkiu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtkezdubji.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtyjilgcqa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtpzdekyhk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gtadggztvs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtqcauktem.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtlebnaaup.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtlijntrny.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gthcbsbfkb.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtuczjhaza.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtkfzmpklc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtjmjoaeku.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtnyolttry.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtdbtoiowt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtandrnmsa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtnjxiraap.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtogyicubz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazerjgix.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtxcimnzmb.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtlwsqynzj.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtzrozoujs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtknkamfqm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtfieytont.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtwpjaoyrj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtvpcrazyi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtwiytxcwj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtplgqucmg.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtfijimban.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtnwincvyo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gttyyzrtbc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtearzibun.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtplrcalwr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtigguapcu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gtkuihkufx.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtyknestwa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtpbnxekse.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtdhdvwhpz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gtvsvndxcz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtwbhusaku.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gticaiygcq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtxrucrfhj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtajivuzen.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtlgorpjbg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtzhyqario.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtgzmiusqt.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gtnzucrikw.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtzwsjwzti.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtumxlolih.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtaluvmgfv.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtxptgbadq.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtjhvdgoll.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtuvzwatnd.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtrlnhevmv.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtheanbyay.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gthttcdqpl.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtldadcrjp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gthleqogpl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtsbyjsrgm.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gthibfubyr.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnikzwcif.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtjurjmdtw.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnehnsedd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtjtsefdpi.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtuygwqpzz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtdkvvgnft.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtltdgzoyo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtlatyvhlz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtbdwqovcw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtkeeenmoq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtgcfhivzk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gteqiaqhuf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtqduwbinn.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtfbliuujd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtnyfdddab.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtqizxakht.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmctfaop.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtnqllcfbp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtuhimpjud.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtaqnbxexe.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtfgijgxqp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtderoaqqo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfquhfknr.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gttmoktgnb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbnlgmhd.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtgkxmlllf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtiekroviy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtnlmxkvnn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtaxjaykjz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtgghofueo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtpnhgxyyc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gtqxkdxawa.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtajjzlxby.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtxpojvhhc.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gttzkzmrxr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdtrxxgh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtopuhcwtu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtfdnkjvce.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfezmyrsn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtsfhhuiib.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gtdqpfoxyw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtfbpebvnn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjomwgxka.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtsyyygolm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gttcujowcr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtkustivhz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gthcwdwnob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtblpwnqfw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtvgayrmuy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtsxxlwial.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtzvyygdsm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtwfjkgulu.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtyhpmjact.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtpugtnjub.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtckrrvcts.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtxfklddhh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtavxedleu.html


<!-- 参考信息 -->