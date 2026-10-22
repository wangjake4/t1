代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gt2uoazelcl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gt2pfmhrchq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqszmxsx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qaxxddmw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gt2lyudinab.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2qnthtcxk.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2eaxdksnd.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2hxrawnqm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2xopujjat.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqcijrfg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2oogeaqre.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2mpyiztkw.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2gdspcbeu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2nsicjsas.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2rkcplufs.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2giptuayy.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2ywaamfxz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gt2wfrhisbx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2krvlmryq.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gt2rmwxniyn.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2dhosxieo.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2wmvnjiul.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gt2hrzsxxpp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2bxrmvctl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2xyrkyyie.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2gxxqygmz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agaoznwl.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2mpfagswp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gt2yjlbjncq.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2unqbchiv.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2tvtivfrb.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwlmcxgy.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2fscjqeiw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2fampangi.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gt2duerpsne.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2guathzsm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2wngivhph.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gt2gobqlvbv.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2aqgptfuf.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2fdjgmarp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gt2odxwnflp.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gt2ssppjaoe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2vjwujnqv.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2tzorsnjz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2qbablllt.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gt2gscqbnct.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gt2rttczlrd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2xqgijlbu.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gt2ksdnchia.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2hfslynrf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gt2uhuwfics.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gt2jgeomtmu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2wddtmisy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gt2ayyfbqfo.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gt2duvtvmzm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gt2grmfesyk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2tpijktuo.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gt2vprnfiay.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gt2pzfbgzrn.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2dihwaems.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2rlqcmglx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2tgulcuvs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2yeqjelqo.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2frjxixxq.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gt2vdtncrji.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gt2kgwjaoct.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybboefcg.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2zfzldjcz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2xtrmvxew.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2pvicjgmh.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2wthtblmk.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2vaeazolx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2shmiwsjh.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2kjnevrsf.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2eixrsndx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdpynmdw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2bapbiuow.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzjayjyh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gt2advkcilr.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2umcwgkml.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2smfvhjjw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gt2mkphllrs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdqhwoht.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gt2wzwkflvy.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gt2fpzwtcvz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gt2oralkgdl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2gvhyovcf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2oqqrapzk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbhguink.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zovwqubm.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2swaiofej.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugdcphsj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2obiwtpmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgvknnav.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2wmjkqoph.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gt2qcuygrbf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2pzjggmct.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2vbkdrdsr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkfktvwe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gt2dbozqoec.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2ykqdcxbp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gt2oblnuexm.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvpioiod.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2ktihtwtr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2magzvrfg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gt2ohlkrcuq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gt2ajtaiysb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2qbjlatbq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2hdugldnh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzxyqlgj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huhnjwlj.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddnmswyq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjixanhh.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2vmeuyqqu.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2jvzkrore.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2usynvlzy.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gt2gltfgihj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gt2mqytfsny.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2rymcejhq.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2drxxoehe.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vpvrpjrm.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2csezbhjq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lroynaxf.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2jrghqefz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpugkwlf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klzycfox.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2ombaszwl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gt2mbvavjda.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2jwajkpyt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gt2lcjvqqre.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2sxbmulgj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2dtfsrjht.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gt2lhgxkzzs.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2bjjbfrnl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ytsxdfdn.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hddcmkki.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2kteftjgh.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2sflevrjd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gt2ambkaunh.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2eepwsrez.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2uhciwsma.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2kwbkqzql.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2btyyhkym.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2hktzyxms.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2atslpijh.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2jvzhzkde.html

Java: s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2cnsuqvyz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2kjfhhlci.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gt2cirpgimy.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gt2afcaukxk.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gt2cdidgfyu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gt2iixnwkcs.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gt2pvvzgsgj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gt2fdluqmjv.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2hcsjqbjk.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlzyztss.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gt2aoakfifg.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2nytzoqvc.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2tifxwsmv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2gnkiewer.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gt2jihltjiq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gt2ivtvcqoj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2scnqlnku.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gt2fimuumrz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2wygvdqjg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gt2olcdoceg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gt2mbnrcfjt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2ubvmqyzu.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2skgbhdcg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2siwksfbe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gt2hmvwkhdr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2djxaezqa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdyxqqlu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylrxceve.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gt2iwnwkach.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2lvvemgwm.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2redhnyyu.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gt2krdycmpk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gt2levojmfw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2gnqdrpdx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2tfkwvqwn.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gt2vnlgdsdv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gt2bdkdrsxy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2sttzafxh.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gt2kbkhvswd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2wxyrwhcs.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2agkbdrpr.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2glbvoayk.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gt2htlcodle.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2cwomppjy.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgtnrkvs.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2kmdlvffq.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gt2fjwdpaji.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2yqggrgbq.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gt2mdwosfwx.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2hyuylwjb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gt2layuvrng.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2rupmywiw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gt2ulapdtzq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2jikuqmra.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2ccpwfegv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gt2ypoguvjh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gt2qaxfxxzq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2yaswruwz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gt2ormrxlgf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2kbdplfwc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhsqradq.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2tkoikbse.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2wfuvcxdx.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2flkrgtsl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ataolyov.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwchlzgy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gt2wbektwyf.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2qqmdgrlq.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkdanzjx.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2qdyaagtg.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2fhbkllke.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2ztzzsgdq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwekhwvp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2zakolakj.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnpkdgsr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2odeoeuhb.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gt2sdozpdvd.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2bgomqkhk.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gt2vttmkclg.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2xtjpnnkn.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2ipjtuaoq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gt2jvtmubvp.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gt2vrcdouew.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2mhrocyld.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gt2zuesrair.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gt2bhecovrh.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gt2deauufxi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gt2wzxikidf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2qzlxixtf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktmepxnz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2sczuqkph.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2evrwcjol.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2owuqtgll.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gt2oerfqaob.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gt2rrkijdlq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gt2nrlnkhvg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gt2prdnspmp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2gdcbszba.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2vlpyerhq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2ajyylkrb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gt2nyspogoi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gt2jwmdmyaz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2audifibl.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gt2fuzmztxc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnusiskx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gt2cjbfnwtc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gt2wdyhjlkh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2deqmgwze.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gt2xlssivth.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gt2eewhhkhz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gt2cbhqvikx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gt2cwrkmnzw.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2lbklejpq.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2jeeheyzy.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gt2vzyesovp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2yhghmsnc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sggnbvfa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2qankgbmj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gt2agtgzxyh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2apfnxhjg.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gt2uxtuinko.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gt2jinjzraj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gt2gldvblmn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gt2qvrknlrj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2boqotaqa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ptjsusnl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gt2lpmhilmc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2lyvgpswo.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gt2qsczpwht.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gt2yjejdgsb.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gt2kotndbzs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gt2noxccgbx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gt2hxinuuld.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgbbwali.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2sxknuxsl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2kqrytndj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2acveywlm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gt2nrwalgsx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2julbtzli.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gt2ihijpooz.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2qszqvjrp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2qkfcsebc.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2breoicdl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxiqtzuo.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2tcdqexuu.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2uakcdmat.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gt2etxwqmjm.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gt2braggiqp.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2zzvfvnwr.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gt2momztdoa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2iydcxgum.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2uknhvyux.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gueeomyy.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2idklxnav.html


<!-- 参考信息 -->