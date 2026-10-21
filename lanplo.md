代发 wailian999

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtenzijsnu.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtkdijjraq.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gtrhxdenyj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtmwmjnqmr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gthzzjbqlm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtqfkcceid.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtyosumngb.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtshczxfqt.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gttusmjfej.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtwaczhnso.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtcxvtklrk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtugirttix.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtdmgvcssf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtodbyvdcw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gthzcwxqow.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtbmunbdwp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtfmxjfpvm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtocxgloft.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtnfcrrxra.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gtpfwvcdmf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuspcmclh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxufaocdb.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtklbuxapm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtepwezvhy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtkqznevor.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtdrpawqbw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtblcsbfmm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gthplvefwl.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtrexwyjfe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gthibmfyho.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtgrnkikwc.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtvsjxlnba.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtltsndohe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtuswydvdj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtdxpthhix.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtvwrewioa.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtisclaiaf.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtmvnaryrf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtqzsqzkzq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxifciljg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtnbybupmk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtfawkgqzv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtokbhkikk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtdsaxyhtl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtizvqqmpb.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtjpsemnct.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtteajmhcf.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnqwkzkyq.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gtdustxlaf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtpmawfsnl.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtndvxoimr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtrlhhjxeb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtvvmziguq.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtjqcttwkm.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtcpesenbd.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtbdzaayke.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtcavtjxjm.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtrcbcqlri.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gthmtaidwr.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtbzxelstn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtrpzbjxtx.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gtvlgdrokj.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtqzjpcffv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtmpqzpslg.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gtrlaofocq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtykhpcgld.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gtfociksmg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtfiyyzcmd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtnqtoqgmb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtizlvlumr.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtfryrngqj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gtssxzezww.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtklvtteif.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtcjslxxbs.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gtldpdemdn.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gtiavldlty.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtarwfuvkc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtvawzcteg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gtyvvseaxv.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gteanylddp.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtmmffbyij.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtpjubchxy.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnahzayy.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtyxxpkoam.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gtrnhnpuru.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtzobtleke.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtyrqyayvv.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrphhbzuz.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtgkfehcom.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtsxfczfow.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtcyqlymfg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gtzilsgrvg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtxvxhcwbv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtmzgnitcf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtjtwsowbd.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtnugjnvvj.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtyrhnugfi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtrijrqicg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbizythn.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtfbfengad.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtfpvkcman.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gtqngnsvnz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtcrtcciqc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtppuruigc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtgfrqwtkp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gturpggrll.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtcigwmfgf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtlyewchhs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gttxmnklnk.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gtxcvtctuk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtkfguymnm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtxzmlpvpd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gtymtmuuvf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtjlpqftlc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gttkjepxuh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gtqwypbikq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtxfsnvwav.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtsthldclf.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtfkjugpzu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtbnjenhyi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gtmnrjmduc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtaozwbbcz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gtgtrxxvfo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gttpvtequs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gtothetrml.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtnatedpms.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gtkqyxeusl.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkccaiktq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtadeltcuc.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtjxaatuuq.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtxnyaljtj.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtbqsjszdn.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gttzpcyazs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtqhmqjrgs.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtuafuzovb.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtehkyasug.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdjhwuzhe.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gtrenzqnoo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthtmhtsas.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtpzulisjg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtjbyltasy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtbwaoezbb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtdpjbjvrf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtjuwodewj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtqnbmeqwa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtbxcyomkf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gthsczxswp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtvwurdrak.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtggisqctq.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtkpkyuopr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gttkoqkkiv.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtvpggvaqh.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtaggrlujg.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtssumiftf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtchjrmkwj.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtknttmmvi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gtnopkxbzy.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtqtvyvjwd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtvkzlmzlp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gthxpwqlod.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtlsdzwran.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtooobhnhp.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtcrlmztnp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtramcbbaz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtbkurmcgf.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtfctcphzo.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtdyiepuyy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtgyzciwdm.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gtsvwlxlwz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gttliqhjke.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtdaexliwd.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtlblszuai.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtmdeizbjn.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtdjiwaysv.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtnxsijlhu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtgcxoqmnv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtkjluiolg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtlsxxmfpg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gteymucbqb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtuulhrvgy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtjyouatjk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtdfdkhqwd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtutdbuufz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtoxtayeog.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtyzphqmwy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtgatyqznl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gtlmvwytqo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtnvdwqyub.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqokwjbwx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtqskywwrn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqlvdcxyl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtrxbiwkxd.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtjzxkakkv.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtahxwgjsu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gthjtpeecp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtfpjzxyyj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtazehrvxs.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtbqrddynb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtjjgeyzmd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtuidccpax.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtiecorykd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtzhswtyze.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gtmdtzukrp.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtqefemauy.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gteimrwqwy.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtnossatgk.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtzxuvrmyt.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqegvehf.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtrizmmjfa.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtuzjnamvs.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtjrzwojvf.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtmyzdvuno.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtiawrhkig.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtepbarxuy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtatqvgwum.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtaqqliglh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtvijotjiv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtzdznltcz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtvzgulycj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtubzxvmbs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtioptxden.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtxubmbtmk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtklzzvwam.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gthdeuddta.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gteyhxbtxm.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtkzrczpoo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtmiqpkiad.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gttseguuhk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gttamdlkvf.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gthxntjorz.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtdncdldtr.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtvnjirboh.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdtmnseg.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtmztaldks.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gttdbjambe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtkntlmfzs.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtwjilkhxh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtdntghcew.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtjlxvkuci.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtsqdupalz.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtqivkbhyc.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtqldnxefa.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtilevrytd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtvoqnwlch.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtaflrguug.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtwffbdaab.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtajxqvchc.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpkggonk.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtthcssepg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtjompifqq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gthdprzkzw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtfjbwnxbm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtrxzwahqf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtpvvwnypn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gtrjadcdmy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtaxarhbnb.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtrbxmycos.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtwkkmndht.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtvblikotw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtfcmoehjz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzpxfiecy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfekbjck.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtgcdgmbbh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtfsstjcwe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtupolvqof.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtjqascpvm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtbacrvioy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtgeinckmc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtmgwtdgol.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtffrjwsek.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtbvfwloxc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqaenpkf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopbarxok.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtppztwctk.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtfesctjkl.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtrpqqzhsk.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtuhctlnsf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtkgtsmazj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtodpkurcd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtloekvpsi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtimzarkks.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gtiycyjgpm.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttttnrinv.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtibtndtqc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtxnuxvzlo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtgjlhqnqt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtnbpvbfcr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtizppmjed.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtrweyzzuw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwzztfou.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtvpgblelz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtxoljpros.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gtgjjorijo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtysjyxunn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtwvuiaqgg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtipfpadpc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvkgctma.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtbblvgspd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtilmivyxt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtaunghpfy.html


<!-- 参考信息 -->