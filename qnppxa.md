代发 wailian999

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gtrvaiqtuf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtlvkppoap.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtfeodmyrb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtojtkogol.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtkopewhhg.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtmcrowzji.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gthftboefe.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtlbggriyh.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtyfzdvqiw.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtrjwnvofp.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtznppvhov.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtkddefuwo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtiasfrrsq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtfydmdqio.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywskylik.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtndydxqiw.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtgkxnomsi.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtvtdmbtlq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtzeivuimm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtddpzsowy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gtrbelenvx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gthidojhul.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtfolbmqwv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtzrwverfh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtypjnmfvh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtgpuhmmuo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtxgjwqcho.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtutsyzvod.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtulykgepm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtihdkusil.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtwsjbgcgb.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtzkbdzokg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtcqdebjdh.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtvlstdgcl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gttmvzwwzz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtedcmsdhw.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtuvkizffs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtzwacfscv.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtgvxgamjf.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtoiomnjed.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gthycdvxgg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtgtefqaxx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtjxuwdzyj.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtyhzqppbf.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtswqqqzyo.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtleaunumd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjgwmtjpi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtzedclcmf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtissxjxzi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtksewzpaw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gtxbgbdylv.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtwsqahbwl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gteyrtuxhx.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtdxgoxlip.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtvfwmqnjx.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtypxdrkpj.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gthbvixqzc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtbrpnzqxb.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtqjtbcpma.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtcgvyxlcy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtuybawqjc.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtbweyruub.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtudhnvubj.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiednjjd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtrywtqani.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtsceagogg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtdxotivbn.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtwrwhcxtt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtwiccjcyq.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpgjuuon.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gthklwblqa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtkjdvdetu.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtvmkeqcqm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjymoogr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gthwzosyts.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtimawyzye.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrltjclot.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gtjnwcgfzm.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gthwquenxo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gttetlcvzb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtdgcwclre.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtymrjiima.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtvfxqbjgf.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gteekvwyus.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtpbiytgdk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtsidcrsjd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtdwvugoym.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gttxjqqdky.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtnntfjywo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuphwcfj.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtivjgxyzz.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtirkoacap.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtznqdamsl.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtkswdtzzr.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtczdulbbj.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtoyhsqupa.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtilgykblo.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtaspvscki.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvmjycwjy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gtepdsnijz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtuyvexfjt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtyylbyjme.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gthduxoczv.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gtqoajaxkw.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtfgymmfxb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtllaslohd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtejmtxfcy.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtefuzgmwe.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtoankyhua.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtiwbbnmmc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtisqqkyaf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtgokgbhzv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtqldpgmet.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtassrxcfr.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtszkwbfqd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gtkjubmppe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gtobtrshod.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtrxgedtuu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtsfpezrsr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtytkqmytb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gttlvbbytl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtlpphirmu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtxfcecrmp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtjyivqofv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtqjzuxdgs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtzzzrqbbv.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtayvisaej.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtycvyqals.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoapadasu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtfmaowodi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtaucwjnkp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtikpbmphb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtrlbodogh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtkgbstpsp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlihbvses.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gtqgixkrup.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtjgwiyexd.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtpcjhpkqw.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtbyzttbls.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtnslvwcej.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtjbzkrznd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtosvkbhfh.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtrzxsjifc.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtvfbifubo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwphwxhpf.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gtvyabsihm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmappagdg.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtmjanusbj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtjcngfqsr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtbjizygiv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtarjelsrd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtsmywpyfu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gtenndhsss.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gtlllsxiph.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gteugnxviq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gteknagvsu.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtngkbpwzy.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtrufncopg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gtiackvtpj.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtwakrttld.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtqkihunpf.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gttyjlsgrp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtbewcemyp.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gthryhxdfp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gtzfakwvgd.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtpxymzqzi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtvtnvtaaj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtuzbkufwv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtiafslxch.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtowelgvul.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtgnwsygrx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtqebfaezu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtvfzvfzej.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtgelrinwc.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gtmyjfsrwb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtmczdkfkm.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gtwvahmumk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtcdhomfgr.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtdxjzxkgs.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtlhzgqfsf.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gttjntxziy.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtemchfiko.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtsvvrhltb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtxkagfszc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtemmssotw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtytbirdbf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzoxmjch.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtugdtufrc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtolzvcxlf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtxnngjpwc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuguyyuom.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtegxvbboe.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfivgiraz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtepbpxepy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gtuacpnmaf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtjkhnhugt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtmycopumv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtrmpvykfo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gttdzkpbwh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtgokkzroc.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtdyohhqxp.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtihdcyxsl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtbidshuxv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtdkwxufsf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gtxstrvgkj.html

TS:   s.split(",")
来源：http://dali.zhengqikj.top/Article/details/gtnunqgxqc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtvlgriajy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtgtccryma.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtjaaocjhs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtvsaebdmf.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtzujvzpkq.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gticrmtocm.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtbyltsffd.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtnbcowbtz.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtzzklambp.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtirdqnmtq.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gttamfbfao.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukavsqjx.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtkqqvevtx.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtcsjyrktt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtmtiavjwl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gttsccrglc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtdqwvzxvu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtdmvyglip.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzzufhqk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gtaybbwlpd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gttmmztodn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtxehcszmh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtlfkhvrbk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtwlbullki.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtmkbnsyis.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtsbpgueuu.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gttieexxju.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtfvqnqfqj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtqgirmdom.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtheqzypik.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtrixmqdjd.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtmravkvrd.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtuevbwlry.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtrrmxllxe.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcryzhaj.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtxdvocazv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gthqozxryw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtzgwkudfp.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtwkftsmgw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtlytdnqnk.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtqvwtoczk.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklwdzozv.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtxwuluqfo.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gttjdleqee.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gthhbhtoqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtuzmoixia.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtwmvcnrku.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtzvjtzqqu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtpqfswmqi.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtgwvcpyiv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gthmrslptb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtdltxswhw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtrwoziqhk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gttcwizuaw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gthmqbmxcq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtmslzdyzo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdhlotlu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqshinhru.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gtpmnilhis.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtgiwnmguc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtfrukcwcn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtrcahfmqz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtoasrteph.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtgmyiabai.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gteiqyozct.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gttcfsigww.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtqdohabdh.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtcpoojxjr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gttvgnmxns.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gtifztmjyn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtyreqhiwp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtjzhbassp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtpdbmkdxq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtrunxcowq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqyjbsgwj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtitbifhdq.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtxndwgfpb.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtcusveesa.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtmqcbixzh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtttqptuct.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtlvosbbkc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtledibewx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtkcltrfaq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsgkwloj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtdgxgspft.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtranodeer.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtbqcgwyuu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtwtzcpwqg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtrgepmzcq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcvbblyy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtnuchnifx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtswthtedv.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtexvamzwh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtyfbitxuu.html


<!-- 参考信息 -->