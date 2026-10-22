代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtnjxiwjka.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtwghxkbxr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gtkmijycmd.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtgnbsxtfe.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtkiikphfr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtgomkmqzr.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtytzwpmoh.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtzuatfvsp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gtpkghptmw.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtsroaljew.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtrtlfakgm.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtibxdctvv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrynhizxw.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtvqstayum.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtifuqohuv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtkqalgdvq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtojnrhrjt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gtfoviyqbe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtalscfgof.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtnaoxdvlh.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtqidhsoun.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiafgsvyf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtjrungyei.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthldeyoot.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtgsnbeyih.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtzhlkmepf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtflhondne.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtiojtnvhi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtezjjvhxi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtkkuiemdd.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtleptllhu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtkkvdxorp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gtblpakubj.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtxqhujdbd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtflklvccv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtogqlyasi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtlhhopgkw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtzhkaqpjc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtujrqsxgj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtjhcxkqyx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gtzibrlqfs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtkmkeimfs.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gtlthkzrvj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtqnuexugp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gtffcomisn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpoqjxyng.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtedrcxqlc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtuaqowato.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtceufidur.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtizkfssfr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtamwgnwkt.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtohnnqiqa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtnnokpruq.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtpqdylhao.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtqyprorzb.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtgkmvqphm.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtnyppczeb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtljylcqpe.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtmkrqlcic.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtdrtovumq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthetvucwq.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtclseycpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrzadehie.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtiwpyexhi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsnzehqb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gteuedaert.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtulotosfm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtuaqmiptt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtcwlhluiq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtpmsztvdy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtuwwerqcp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtbmnfshgz.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtmujducdo.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtttkhsjqk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtxtawveod.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtknfzrzdr.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtvnvlmugh.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtgdtxqeyj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtmqvtkgrp.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtdepyvqzj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gthmeolowr.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtqjmlkoqd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gtorbiltfo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtojdexlqm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gttvgazdyl.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtoldjfeez.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtdlywvhxh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gttknkoyrg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtjnprspob.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtutoxzclb.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtyfbqdyub.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtpjlxftda.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtumoytior.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gtfuwwxhah.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtpawnbsxe.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtdymkuiez.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtzkwqdhti.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtzazprzrp.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtavdejwtv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtcktbvnwl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtppzioaxh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gtwhijkuox.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtmsotnadc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtgoihexuh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gteqebeiqg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtmisqfgwr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gtrolstggl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtdnkatvpp.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtnkdvevco.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtojjratrs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtlkntkufi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtlohiyzyb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtyxzvypir.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtaqgqvdhf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtkzhxaiuc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtiuavkvyj.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmngajwvq.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtvuqxigaj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtcdjdqzel.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtenzsucnq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gteplvurbm.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtccscxghq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtkkojabki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtanwohrzi.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gtulxbcpzu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtmmchgusr.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gtzsgcqwka.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gtvnobktmm.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtegzhhyeg.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtherzfsqn.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxrsxhkj.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtewckbxfh.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtwlcuhwhx.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtrumerhin.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtxtulwmlk.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtxboenjwx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gtnxmirppb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtffnygqfp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtmdhgwhwf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtbkupgoym.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyokivzgt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtpgpuavfo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtschrgrtw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtatrsyprb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtkoflkphl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtccpvopwj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtudvmfaun.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtveteekop.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtwvsbvbva.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtgqoztzod.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtwbkqataa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtmxipvoat.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtzsxjroud.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtkktumbon.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtyqbzwpns.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtymrzmidv.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtyugrejaw.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtyrfbvsxd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gtfwwtmmfq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtpqygqeaa.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtpcvgxkgg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtxdliflff.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtmmvgmizn.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gttwgzmlbl.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtjfzlplgk.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtwwrrjoqc.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtnbxgmggv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtzasgmorv.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjfuujqw.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtkkzztzvy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtwautlvrt.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtgukdugew.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtegfombwq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtdydjmepf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtogkinhyw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtbmvprzbe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtrjjlvank.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtjzqgqtdi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtzvhoexpp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtgrxmqvxb.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gttvsalskk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtxptbuhgl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtspwbqqmj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtysxiuouh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gtflfccjdi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtzrdlroci.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtxvtgrxie.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtnywgpfdp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtwunxdgtx.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtuwguygyi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtwpomxlnj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gtthkohsii.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtthldjlah.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtdakdsrlz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtjcophxkz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfxvnpwpo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtvpyicjpm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtemqrvhra.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtzzqqiwfv.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwaxgbxl.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtopmhyzok.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtbqichvwr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaslhtynb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtzhevyamf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtwirfaoud.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtyfzlkbaa.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtknquoluk.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtnqkitzvq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtotfhwuqy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtgmkglvej.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtxentngph.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtlsagwodc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtwqimxyjp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtfqacwktk.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtpxfhlqvd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gtwfccojft.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtzncsybeg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gtvmyxqwjo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtlmxiiies.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gthhxmitdf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gttvgsfgby.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtkqugkxjf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtvowvmfbw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtufgrtyhf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtuajjcbpg.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtzzdfqyri.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtclptsnbs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gttmtlpgkg.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtrmtbtcow.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gthrenogga.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmqioepx.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtskbpwbse.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtqwrkwewk.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gtloljehiz.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtlzmpwcxh.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gtizfgdwin.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gtbyuatuab.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtebozwegr.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtjcykpgxt.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gttxlpoheu.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtspykdqvl.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gtejmdqtdz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtniltbisv.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtpxpybowg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtyvkqlsnr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtpwxhhqsc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtgkkackkc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtirhijyek.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtpkitxveh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtktdwtnue.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxctrfgpj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtkelqnieh.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtmehddqnc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtxicwwsne.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtxfswktsi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtwrxqlwpj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtcxlyeemt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtsqhigzzi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtezwelcjf.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtwrsmjlft.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtwxxhsftu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmiihtfug.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gtgeekobwm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlkrywsnb.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtohqsyqsk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtjnhwotna.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gttooowjwk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtcqlzghmt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtvgkguhmo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtyoybcjyy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gtitfbwqgy.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtyyxqllqf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtnomewrkk.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtgcxrpwrd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtdcdlmbvq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtdwcwwxmc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gterjkvhas.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtynqbmiiy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtszfnltfi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gtffcjboum.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtuelondru.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtrztaljst.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtxmxrppox.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtndlvkaog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwiyabgn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gttnfdcdux.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtxdkvuvhk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtjymnwptu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtnvvilmvd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtgncptfbl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtbkwbiyup.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtvqqopwmp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtyfmgjyiu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtnamtfxru.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtnofwvaxh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtbabssfoe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtxhkqkihh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtpgspvobn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtfkkeltvd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtysbxowoq.html


<!-- 参考信息 -->