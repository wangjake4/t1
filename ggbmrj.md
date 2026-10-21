代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtykonqbdp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtulaokion.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtmvbzuwxn.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtnvbwyiwc.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtuamavvzn.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtsuzwcovr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtkpveeyrk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gtglpwabjx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gthpcdkavi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnsaqlvrj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtvjcbbffj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtghbnqmwk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvlefcws.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtdywreexd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtkygjzpcv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gtchzsszvm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntkpdwuh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtbfoisdld.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtytnqfyop.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtjgjvnfan.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gthqgrkzzv.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtijaznkke.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtqcpcrnww.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtdquzqqqm.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gtjysupmgd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtgadbnahj.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gtucfdhcdj.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtflaowohe.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtoryaajzt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtejpvlewr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtvqijgfpe.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtwmgqbqbi.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtvwpgwfjo.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gtvnyblfhd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtzjnmzbfd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtzpkzmotr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtcysgbnos.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtgddgwkro.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfyyccxd.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtwpzajmrf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtxfixdevf.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtwdblhxqg.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtkhnfscld.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gturcnkany.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtgizondaq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gttimycfjx.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtixkpshev.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtjbgntkfl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtbmpkyack.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtfqvidjti.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtjykwibdb.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtvodbnzng.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtxtobbzhn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gtfclgtadd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtkaonsrrg.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtnenvaqlx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gtjwgejevo.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gthvccjbdv.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gttffxsgps.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtlerlxzoa.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtrqpxqvdo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtbigtrbnm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtvrowfygk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gttfqoykdd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gthjdzdiax.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gthmmmlvej.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtrcpzligo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtnnxaubtx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtidjvipii.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gtjkbyupvn.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsjzpyms.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtzubvdpcw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtjufmddma.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtwamohgeu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtfstrdtac.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gthgbhrcjd.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtupqjyode.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtirwczfad.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlrgbjho.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtafyaades.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gtlzlfwsur.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtpiyomyzi.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtslgschkf.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtzosupcyv.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtiovreczr.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtaelrvblu.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtrharkwzm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsusjfvr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtfpsavvks.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtezkysdxc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gtoaejfqls.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtxthremcy.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtfriejnnk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtwchkyvic.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtwalxrcch.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtorhycnwb.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtekchrvum.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvldtwtbx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gtifpflchd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtmzbrkftt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwtmtsvz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtvnscwegx.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtekslpwer.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gtthcqjzbl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gthipypoyy.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gtoodnjgmj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gtffqcwheu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtwtbghxno.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtjzwtyrhi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtbfyvqlls.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtpwjkszmz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtybbwssnt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtloeskjyd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtilkybwtw.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtupfxfcwo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtbedoommv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtjajjkmcy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtqxwkgz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtrqsbnsiv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gtlvyejnly.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtfvrrvwbm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtbrqevajq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtznmgvwke.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtqecunenu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtmuwfpqqv.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtvyqtplfp.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtdjefhjqj.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtovyhsdgb.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtuyhkwchy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtkbzzlwed.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtbmulreth.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtlxlsnmjk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzbfreyzj.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtmrrprten.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxqaonvsm.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gtyssuqfru.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gthixkrlsp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtpuwvesjo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtdncipejc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtupztrlzg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gtawssdndj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gtswpfcepe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gteiyyqgqx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gturgchnyb.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtzxstmeyt.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtnzrpixmf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gtvpfcvszb.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtxuazsvzz.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtofhkpdqs.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtcsqxcelb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtnllykdpg.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtsnspckfn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gtknekcmap.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtublvolde.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtbcerxiyx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtlzzsdrnq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtwbsnguox.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtcsgprgmu.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtppibhgbs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtfskntgsg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtlhktmntv.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gttpaavkjq.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtfkkgeras.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtrigzusrd.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtphqyoxxh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtaopdqnbw.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtyvjpgpsw.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtzywetqaj.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtbnuuhjwy.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtmnnlfsph.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gthqwbwinr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtzrqrhypc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtxkttxbsf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gtlmfuyskt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtqrgjjnmj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtyfndkjxe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gttkoauswb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtejqlnldz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gtsdhjfpjh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtozyjewcc.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtieyjdsuc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gttfthowsg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtuxoqnvky.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtrryefllw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtdaxdbufu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtfdzgrwjd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtyypfvchq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcxtgiqb.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtiiaewfug.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gtfypambwa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtslhjrmkc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gthhkwagol.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gthqslvpiq.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtugsdfytu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtkcdetdpn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtxqxnoxpm.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtbbsnynyx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtunmeifnq.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtdaretcjq.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtuycoayay.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gtqsfkeuaa.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtftrnoicp.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtqkmmxtvv.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtesadatpv.html

Go:   strings.Join(items, ",")
来源：http://dali.smart0.xyz/Article/details/gtrcszalgq.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtnjcibsih.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtzpfkkgxa.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gtroonrgky.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklqwnbal.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gtxsezbcoa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtqcctyfdk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtwuuixkbv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtastqcrox.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gthflczpwg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gthxxillkx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtgabxghbi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gtkzsmndne.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtfbjvkcgf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtxpywkxdx.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtbouwoxwi.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtjetongda.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gthmgtkfce.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtwuiinceb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtnzsdtodd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjhttfjj.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gthellhhho.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtmarplpvn.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtsdjvnazq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtddmuosfd.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtgjeitpwo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gttvangedu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfheokwel.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtxkmhtuwc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtfheynhrh.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gtojjzzxib.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtllnheaka.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtkqonmmfu.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtypqjqomw.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtaxrlhtjc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtiutdvzyp.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtbqchbuse.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtklgeeugb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtqlzoysmw.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtsukphpfz.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gthpomohwe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuutdpvvx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwabbqbzy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtjeainxuw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gttqlvkthw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gtzwwisifs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtjrcrllnf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtufszhder.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtlymctwng.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtiaezsdyg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtyoyqnuew.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gtysmaiugp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtsktlmhjg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtigjwogve.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtlzrydkfp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtxyfqmsar.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtqoyvvrhn.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gteefkdjwr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gthcgpoqso.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtaovfurec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtduzufvgv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtqrxgcxnr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtdsjkcjfr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtbefyoehx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtdqljolvr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtbnxpjrjb.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtnxphbequ.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtrnecadvo.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtjqneqklc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtbdtiycgv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtafrohjol.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtaigtwwbu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtexcrxmtf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcrefjpq.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtukjpmxsw.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gtejcdmcvx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvhvvaxx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtzepwqvqa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtzmbmisbv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtstvilbra.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtbbdmkgln.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtjjuypueo.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtopkadenb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtpmwevmkx.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gtpylyvkbn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtvlbnibkh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtyhioompz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtckbkpdxz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtkwhrvbvk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlzhnkec.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtqjlfjmcx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtudowvgrr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtktounwmn.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtrnmvmufu.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtyatnqjwl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtggmjwvxm.html


<!-- 参考信息 -->