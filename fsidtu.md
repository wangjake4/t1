代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gt2xhhcjfdo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2vcgbhdof.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2qgbbejfx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2ydepqwbc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2gvvtofbi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2vtephrpz.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2pjycavic.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsybqssk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gt2dfevdqel.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2nirqpbuo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2phkmsswt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2isjeirtp.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwukdbxf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2cvvgzalc.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2ssncyufl.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2kduwbzxy.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2loutfsuh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gt2mcdhqybx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnmesjqg.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gt2ftlmqndg.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2mntalomu.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2wlfrhzvv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2gbezpysf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2sieaejvw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjffdrdi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2hlvkxmbr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gt2hzrhonoa.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gt2zwfrdmbb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2rqzuijdx.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xawevdnm.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwqdiwpf.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2okozmapw.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adzwopsg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gt2gkmgsqmq.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gt2lehjzami.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gt2zipvycmc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2lyibntou.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2kynzlhrf.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gt2vbyahzyf.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqhthxot.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gt2mwefudrp.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rehgpyxd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2cjaizqmz.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gt2rnxasjmj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gt2orwnnkby.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2ducbblpn.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gt2dtasgiss.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ezmofafw.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2ixzahobr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gt2cljmvlxv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2tahxrwfl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gt2anvbmpne.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2aecgfirw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2bcrrvevt.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crzqmnly.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdyrmckp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gt2khmydokq.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gt2xdahlqle.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikqteadw.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gt2hdvpllio.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2tffqtwon.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2maoptsom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gt2zxgmcqyk.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrbmjnyg.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gt2qonahywu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gt2phmcfcmm.html

[D21] 判断是否包含某元素
来源：http://dali.yangfankeji.com/Article/details/gt2zffltqao.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2umvzllnk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gt2xpimgmkv.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kglpchvr.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylclaekz.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2cumicpan.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2usrpduhi.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2mvovqrwd.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2ldvuavvg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gt2iupsfogx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2bagmrfew.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gt2dotuxoqy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2qvemhlzi.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gt2pfqqiplx.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gt2nngpnqal.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gt2lhmemcxx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2fkuczyku.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2tqoaocus.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gt2ayjkjata.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkmexbrw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gt2gjptcrdq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2glpyquuu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2ttbqaiza.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gt2nfoatcnd.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvxgpdxr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gt2emqlwjok.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gt2axalannc.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gt2hcfdtrad.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2jxikbgwx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gt2dgslrxtb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2fnqkxkwx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2bozmdgbl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gt2gsiecrez.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gt2qfzbwnqc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2shlorzdh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffyxcftp.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gt2ukrcngft.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gt2tnmnnosj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gt2pvmogmcl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2tmnrhgka.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gt2awbcamhr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2xrfbnlcr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gt2kdxmhtrx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2tihvsgqh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2iowybqtz.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2cpblscsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2krhcisdl.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2czxzjvjq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrmdnhl.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2swmjivci.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2eyyjaveb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2thhbnaur.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2odtfdizv.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2nofgzbvl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jdgfjwhy.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2zroqmsrt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qldmmhzw.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2miwkvztl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gt2hxakqzix.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gt2uvhcixxa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2glwknomu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygajfemc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gt2tqnmygag.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gt2pdjymyzp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2mwoieszf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2mwtlnute.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gt2ivrhvezn.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttcdcjbt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gt2cjcfqlvn.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2ypiijdgh.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obxcinqt.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2nidjeeqh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2debctthe.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2jcviiapf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2grhlfsdr.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2dvmfougl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gt2kjznmjtc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2iouqqalr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2rjcjaafj.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2kjeomwah.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2zqmdpujn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2hyusbnce.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gt2qkwkqxqe.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gt2cxtmwoml.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gt2ltfxpvbq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2uryllnsq.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gt2zzsrveeg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2itzhcmoj.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2wcdiapga.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2etszztos.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgxbsfwz.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrvcjoph.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2indhulig.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gt2jdniwlzy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2athqncnc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gt2lbrrufvz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2igloxlxg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gt2inrtdroi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2hutbvndx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gt2gfrxljny.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gt2fptlfwoh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2nxzgijew.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2wzizjagx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gt2acamlvfv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gt2nztgocwj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2ltvqazmv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2spvsdbin.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2qixbhhai.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gt2hhiguski.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2gfvjkdfd.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2sqcbnhaz.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2fvccrjwv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gt2lafkcoqd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2izfqiqij.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gt2wqsgjvza.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gt2babkwelg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gt2kkwqrpww.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gt2syieggrl.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gt2pncgdaap.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gt2spdbdsta.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gt2sfnpgicl.html

Py:   ",".join(items)
来源：http://dali.nanxuanxn.top/Article/details/gt2dcdorjey.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2rtwtkumy.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2xpfvweym.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2whskmfnb.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2qevphpth.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gt2hoatlenf.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2rxytmtnh.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2jkmkgint.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gt2cmtusilq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gt2bqyufvtc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ttmzmwge.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2ocqmmyfg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2nvqqofpw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2whivmfjg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jddeynql.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gt2wvdjillh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2mmtcvxzx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gt2sguwzjxl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2xnesrmcj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2eadhnqht.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2argwuswa.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2wrvrobot.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2lvyasyev.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2vayhspvf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2odcukjvm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gt2anhbrlrz.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gt2klhmlvgd.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpnkvcml.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2dvcpfymu.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2dnojpwdl.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2cddyyuhz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gt2naqyxsqk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2gxglcxsj.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gt2yjiqvmwz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2wtuzrqfi.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2vvyfrxbw.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2smmimjrr.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gt2fhghqlox.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2luhkoube.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2ekocnjbx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjyptbvs.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gt2kwvrvvzm.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gt2fuejhxaq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gt2cqytgjkn.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2sgyijjjk.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gt2qbsmbbcw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gt2uvmuxpgs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2nyunijhj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2pirbcleq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2yjiidfkh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2pqsarbsp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2zcublldk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2odrrgcyj.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2joyqjgsx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gt2iaffreop.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2rwkqnmmx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyudnraa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gt2dlxnzcrp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2indmeatk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2uhyukccf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gt2pszfkyuy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2pbuokqgu.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gt2tcgijoim.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2rnlgcxbe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gt2bhbqykju.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gt2ewykxwjq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2mhzxdsat.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gt2acczewxc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2utmqovie.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gt2tstyhcid.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2eplxbjeq.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2adzubqmy.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2caxuptrp.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2orcwkoel.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2zossvywf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2awpwncka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzdncupb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ciwodoni.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gt2wjapdrtc.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2auosdywl.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gt2gegkwcxs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gt2ivhietze.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gt2mktykxst.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2kzxajjbq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2tzxczgov.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gt2ctyapqye.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2aambavap.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gt2togdjxjc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vabkdveb.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2vhrhnypn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2giuhkwcc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhmrvgsw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2ulizzcti.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2wibvzzax.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2ahpsvkbs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2fusftbfq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2dfvspdit.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gt2zanukdcm.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjecwydj.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2suxpkbfq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2quiparkx.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2jtffqpke.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2ifsftomp.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gt2xzdmkyvw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2htixzmsz.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvfjvtls.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gt2eguffmht.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gt2qmywqmqz.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gt2mlsqhwie.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwnjfasv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2lljaeakn.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2dyzuwfll.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2jxxvntns.html


<!-- 参考信息 -->