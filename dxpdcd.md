代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtknvstrra.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtniebejkq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtxtzcegas.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtgyznnxcb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtzpobdtpr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtjwwcqjjt.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtmnjqczat.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtrxjczoyl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtjyzyexax.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtbifjhthl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtnjzqdmml.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtvjijynsb.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gthijlseaz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtyxuouoko.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtlrdefx.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtkvkcjxtz.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtarejhbib.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtuctxdlnz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gtukilchxf.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gttckpvwde.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtqnjfuzxo.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtpyfxatnc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtntagmmia.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtxsbwdnnc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtexzesgmu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtdwvqmcoh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gtccdmyypo.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtliqsjcsq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gtwowdeqkn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtxjpypyvc.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtkwjcasek.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtaxdqxkap.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtfrpptraa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtngcmgymm.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gturydujgs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gtjkfkmcul.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtfbtisqzy.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtsvfmkolu.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrphqqmmi.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtfuwjvbhl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtmtxxvuru.html

PHP:  array_merge(...$nested);
来源：http://dali.dianchejie.cn/Article/details/gtwbhuhttc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtfzrriinr.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtooszljfr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtfmvrrprb.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtznwkjxjl.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtvqhdxnss.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtjdnsxzhf.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtlxwhsalf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtgorcqogd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtuqujbazt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtwgdumixt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtjbcrdqom.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtjcgtczry.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtmbmqyloe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gtxkqzrfcq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtagpcmapw.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtbizkjsyn.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtpmwsaszs.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvouwrogl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtbfygtemj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtipalrfas.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtcnwysukv.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtddbhlvhn.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtjvtbdbjc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtwrxyksyh.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtwrnfsxfg.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtifxiucre.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtsqqwxctt.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtljbkrxsh.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtwnbidacs.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtdrgziycm.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtonerwkdx.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gtvewqtghb.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtewgdswwr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtzlfinvdr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtzczqpqrk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtstmmwhrn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtbimyekow.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjawhhcd.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtloyxahwj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gtfnaljrec.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gtuxzuxjfv.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtuesvvriw.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gthrmqfalg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtqrmjlxqv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtsjaxlhct.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtlgwmeraz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtutwsqucf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtjvinzqeb.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gthszzzgug.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtnsxxzbzl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtoibnyrxy.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtffmoiegi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gtvqfjgrhe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtxoeiozoo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtzntkpqjf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gthsfjhaap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtinwelwtx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtddytgmtl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtqrmsbnab.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtirqqcyfd.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtwcqxqncb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtdwlqoshm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtuiqmfggv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeiztqig.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtgmfguref.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gthxxaqpcj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fzhhl.top/Article/details/gtbungeyve.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gtmefvianp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvtdtggjo.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gtrqqfhuwv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtldhmaomi.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gthhezoziy.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgyurbbh.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtkatykrhg.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtdrlrxoqd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gtnzlgwfuy.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtkovfdnqw.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtmidkwhyq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttwaeccuy.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtjlzpqbfv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlqhbztvf.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtrizdtycn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gteeiyqren.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtgqusenxt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtzzzkxnmk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtkmzmjgml.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtbmjygalk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtehpiheej.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtazaecmbr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gthvhsxajp.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gthzittyyz.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtgxvgrbwm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gtunijtrat.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtgqrmeqju.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcxoyumx.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtuprrizwd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtefpjqcpc.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtieizoihs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtjhkvmwkb.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtzgfvouqh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gtjwlghgzn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtlbzanomv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtlizfwnoe.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtcpxfdwgn.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtekxybusc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtajfcfkbu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gtixtlbrwt.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtljwfgmed.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtjwjtipuj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtivzkmlmw.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtpfimbxpb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtstznckjh.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtyqdicbbp.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtptplrclb.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtlwdxepus.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtlllwrkvk.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtbdifyihk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtqxudwpuj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtuifltluc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtlsbyvali.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtuthylham.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtyeevjwox.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtecougsee.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtsrzcyeac.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gtguvnuohu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtazzhhvyl.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtgiogcjnw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtqnungnah.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gtewrydbmh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtsxjedzzo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtkkjpbkrp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtvxpjfaia.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtivtyqtpa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtxohghiay.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtpkjbvhpj.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtsjiyvhnd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtseakekwx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtlsykgnot.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtglpwauix.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtfipzwxcx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gtjtiilpey.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtoiqjkmij.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtmzyyhzpp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtzpjobngu.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtfmzwnbys.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtqktjkkls.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gtpryaxwya.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtlobmadwx.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtjeyoualm.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtxarmezok.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gtgbeypsbr.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtgxznwvho.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqnfhmic.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtcysaylqz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtditqiiri.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtsrvpbvjx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtgbhhivym.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtsrbgmznm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtwvabgtgw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtgdowkhbz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtutddrqhf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtfsadjwpc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtrkgyjjch.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtxgaotidd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtvvfenepz.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtsjzyinno.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtikentfps.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtyvuecofi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtdlzighpg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtdhwfuetv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtnbwwygva.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtxrnsoqqd.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtdbehplyv.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtcnyxveox.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtnfqljyow.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtouesftmq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtywsabioj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gtdzjluihd.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtparamhus.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtmgjgdhec.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtyipisgja.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtolfcuans.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtdvaxuiaj.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtspdglaik.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtekbrgthb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtfftigglu.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtsybussxp.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtraccpbnd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtquqrgupm.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtncjqeizg.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gthqhowylw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtxavpkpat.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtquffozjq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtlmjqajrr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtnadnfzhv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gtvcollobt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtxnzebwly.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtlxsppbdq.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gthgvittwb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtwpfpxxja.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gtnmiklmgy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtvunlgejb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtrsrihxak.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtdxgjrwsh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtznoxsrvl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtgjznbtsc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtbdhhvqie.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtvptuinya.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtlwaubktk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtnjskurji.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gttqlckrzg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gtfcighqeq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjukqidkt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtoqrlfqsz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtcxrufbwv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtqeszdpsd.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtibostyrt.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtawbkowlu.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gthwltbobd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtpiwnigax.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtlagvhmpb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtuyphqhwg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtrkmtgzqa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtietwhmkg.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtsugijzit.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtpuixgefg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtqrzamlai.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtnwndyjze.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtkyhedthg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtinbyzkky.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gteuvaupxj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtpdsmsejc.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtpuvskxsk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtfflsurej.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbvarfco.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqbboqtu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gticfikbtu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtiwydximu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtsawvyxlf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtgkmnyqis.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtvkocrosp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtanbgyazl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtjrwqrlav.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtvcadneyz.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtdfnyyayz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtwlmhqluw.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtatdpzbmg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtqpbuykyc.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtykkxjppn.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxjezwje.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtghzaikpq.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtclvtohhu.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gtwyionidv.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtwugwefne.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtycyrioum.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzgsxdcu.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtzaozrbna.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtjfuwghsm.html


<!-- 参考信息 -->