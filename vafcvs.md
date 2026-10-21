代发 wailian999

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtmjcigdqs.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtydsufjej.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtoozbycxv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtzpmzkvkm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtlbpvilim.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtdwyyfnyb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gttmskwcqi.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtfguhiwuh.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gtqfpfxcqk.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gtbtkpcyrl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtikagehjx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtkjhkhnma.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtbuajmmqk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtfwhqtbqu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtasuivskr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtpuirhstz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtgfsebbzp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtxcrpvbnh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtllhpyjug.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtfvhieapt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfrtmiso.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtarbvpcyw.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtmhenosev.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtdgdxcbyf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtsaijlkkw.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gthqhpjmxj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtwmacyebt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtngasglvk.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtilrdwbyd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtcdfutbow.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtkkbbhssw.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtxbrhzdve.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtbaqxeakj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtjxywpkac.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cdnleiting.top/Article/details/gtypnvsllm.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtqazzzhzr.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtvzqumgoq.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtwcxvmohd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtmkgcifgd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtebraewow.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtnbjqqxsn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviggfnsk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtpmcgckss.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtqunwusyl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtkxoliijr.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtiarcuvlq.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtyorkigua.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtbopenejj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtcfntvopz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtddektikp.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtvfxoztaf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtwudheljy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtajsfiuva.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtsjbjrmyu.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtwdvozxhb.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gtyibkpaxh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtrzuzezoc.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtkacxenim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtrqlerzcl.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtiormvzgh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtmoabsuin.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtgamqdidh.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtevwhpsok.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtngteyydn.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtjuajffiv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtdfqsvcmb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtpdtilizv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gtfsiprjud.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtlpcsfpuz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtohswluqo.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gttdhupntd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gttuflbovy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtetqxezzq.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtubnaxvql.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtwbdbxozj.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtooodckhr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtjybctjrx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtnprnvlod.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtcoguxvmb.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gteptrqnau.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtcsawrshw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gtabybymut.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhvchcny.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtvufamgmt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtjrsaejeo.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtxqwiilrt.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtuzzeumel.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtpcfbeyrt.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtanqpdeuu.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtamnwrrvj.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtmdapedjo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtynuuojrg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gteerhgtfw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gthbuuiwld.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtnlytaiwb.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtusahplys.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtgdlxmuqf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gttskpxfje.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtemlepgxe.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtrcjdgrpk.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtpjgodsvj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtmtcishcc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtuiprqara.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtsevonxqp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtooeoovvw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtesqsatqz.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqyqwbwp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtdqghmgnh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtptixjxai.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtcntmoiwu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtgkulypyt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtflrbnkqz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gtpffwshac.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtskhsypba.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gthklnftrv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gtfailysek.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtscjjalll.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvdcoonf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gtvritaphs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gtbvwaepuy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gthrzsvicn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtxypidqpb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtplefoftm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtyronoqqs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.feifeiyinyue.top/Article/details/gtyfdxgrbp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gtqhdkmljv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnlfwljwl.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtinbybpjw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtqeaelqyb.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtfskjtmpq.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtaiaojftp.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtyqvjtgjw.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtpisbcrac.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtkpshumoe.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtjflbiduy.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtcenriled.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhliushv.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtyqduefdf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguzzizyv.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtexxzavsl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gtqdfjglmn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtqzadowqh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtzaogzizp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtricspxwh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gtmdnhciqq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtecykymxq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtquunidhf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtgdtomtci.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtxggdmqgx.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpukubufw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtlpmycpev.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtygfaiiwr.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtlnjvxjqu.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtjxxnwvga.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtcsqcyjjb.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtbfdgzdzn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gtaaqmujzb.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtbwcwpnlp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gtykmvvcue.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtlnhyhsbg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtuajrytmz.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtpamtsrpe.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtndqxipih.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtvbqwdwgz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtptwkvzzh.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtgmykqadq.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtzxkrxqbf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gtsryfzlfv.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtcqgjiryx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtramazhul.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtkednjgcr.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtqaavoatq.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gtgmbcuwvv.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtadhqvqnq.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtyxfdzppg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gttuvbwvxa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtuqzmwpkr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtqqayxclo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gteksfvwbd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gticfirxfj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gteicpshdn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtxrrfcygt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtqarbpkkk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtdhdqtrph.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtivfwirpp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcsgzuenw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtezltmkmp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtddrxvabn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtcbxslesv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtpaqdbcsn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtncgxdida.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtqlderzky.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtfixulkux.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtkazfqmrd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gtyorohzzs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtudlnnjva.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gtzsyretnz.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtohoplamw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gtmmkcottr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtshibkeae.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtjuszzils.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtdfyzpexc.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyjizwjy.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtsglkfuwk.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtqcwprqja.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtgvafpbyy.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijblunnh.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtdmspsbrr.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtihmsaxvc.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtkkkxyoif.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtxbtpahxm.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtejyifkkc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtlgbtbvpv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtdmskwmuu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtjbuctwxz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtamzfrbcr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtpbtdfwlg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtyyfgldbf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtuqiyngbu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtxoocpflk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtcxgqrdxw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtcczlxeog.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gttchzabhq.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtpbskahvl.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gttftjcshl.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtyvzgekyn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtkyggchnx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtnfxzjelw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiesfjno.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtrooewzzg.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtkpaamedx.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gttojmlgub.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtvljvfrva.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtuflpjxql.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtrycxbeig.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtpmvpzzft.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtdqnpiaft.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtemcurwnv.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtklwizyse.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtuhrtnfwu.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtroooosdo.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtwbokmftk.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtgfhejmoc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtmyslxxcz.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtoxtmggdk.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtxrbyuwhe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gttzomcwcf.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gteogwajdi.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtmscgufgd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvihvcqwp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtuptppjxe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtjzpfyztv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtcvphdfrj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtkptjdggg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtnyxmquxj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjoivlkbl.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtijylxx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtzrejdjwx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtvjzyvlzx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtzxuttotk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtyyuribqk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpogxqhyt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtpljpsssy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtmkrqoiwn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtrcrfaoph.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtqoywcfuo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyrgcjsrr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtriamvoqb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkrkxivgz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gthuaduvav.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtnmxggjaq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtqhsmhdub.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtegyweaue.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtibkslqxq.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtpoutzyjc.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtqokassct.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gtofxjinwb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtbnhsvfcs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gteuxhfgmx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtrkzpvnoh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtrewkmwos.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtodjvoojj.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtcfjztlwm.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtqwzozhke.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtajkwtxre.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtaaciypbj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gthpzgudfz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtmicqnrcc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtklrorzqn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrozuqyrx.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtqajwdtvm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gtadfkxvag.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gtcwjcuoji.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gtvnevynmd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtbztbrzay.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtztiomvvj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtcrgoidsb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtycchuntf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtlymkauvi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtlesbfopg.html


<!-- 参考信息 -->