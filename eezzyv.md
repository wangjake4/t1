代发 wailian999

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdyupnkh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2bgarcptl.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gt2rbbbhuit.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2ikjzrjng.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2oowgggep.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gt2krznowyz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gt2olcaxted.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2cidzsumw.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gt2mbkavyky.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gt2iikhnbbx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2fzjsyjfo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2dykohbuh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2oatxhilf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2bijwytwa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xecakgmo.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2cjchnhuu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2hqjnxrcz.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gt2ayjwttgm.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gt2uypbaoon.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2qmmfmpcd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dweuifgr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gt2ywadzsfl.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gt2hhykwioe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2bnhphruv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2zovzlwmx.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gt2vbrbzzdr.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziptjriz.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2fryhezrv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gt2ocolgvpm.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gt2axmjtyvn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2yughmqhu.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfqcvutt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ecxkhzgh.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2jpbmtxhc.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2pdntcjdt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2gewcagzn.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gt2pnzhyspy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gt2tuisnpwg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gt2qltxhost.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gt2fkjgywaj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2uxadywum.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2mrnnlsjd.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gt2rdcnqpyy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gt2dhzkyqmr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gt2mpiomaxh.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gt2czexuxng.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2jcljqivg.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2ffwdlrus.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2njzddacn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2uzzkejae.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdqozaio.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gt2vrnmqbnk.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2ysfjgiqn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gt2ebmsvyjq.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gt2xabyygti.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgxovwgf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gt2cxynldwe.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2npijustq.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2zhwairhu.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gt2dqmoxddv.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2ntruoqlk.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwbtyavt.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ddrwjati.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gt2dxruyaef.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2dgelezsk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gt2gjxvymls.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gt2viekpidw.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gt2zstebeeo.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2njpdhmkt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2voqdkygr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gt2zifsyylo.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gt2tjfipvje.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2fqbfiypn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2rflzcdjj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2uwaqxvho.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2eilcfjul.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msealwqz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2yigxfazt.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2gfcvndnu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2gybfwtwk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gt2bhcqatsm.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2hiyahvxr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gt2jvxuerbv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gt2saejzpwf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2czzgmytd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpzswdlp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gt2nafwtovq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2bsjgofom.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gt2lmwhynzy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gt2lvqpjtsa.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gt2opauifho.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaabuopj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogvarzzi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gt2hybmskzk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gt2vvjwpdbv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kyovecgz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntyxarev.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gt2eljhsbzv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2wsgatgsn.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gt2pwlkvumn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2eqcbxlft.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2sildgxfv.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2gahwqzwt.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2axvjbnwg.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2odpckodz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gt2scyrcvii.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2sfctqvrz.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2guetieen.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lcinjzyp.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gt2iggalnnl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mmumtaig.html

[E01] 拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2beegxays.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxdscdgm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2zmnfbmmn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2wovdhemn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gt2wmfgdxsc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrxkvabl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2wyvjtvda.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gt2rmxkbcdq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2xiorhghk.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2jzuezflw.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2roucgthl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gt2xshuoamb.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2qqnhpvwf.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrzbetqt.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2eddpuvis.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gt2cqoovxpc.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2ltnluyxh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvmblvyn.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2yygebdla.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gt2mqfvpxpg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2ohdzdqvh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2nqwsswro.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2mdwlqzes.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2yqmwpivh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiubqsyb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gt2kozggwpy.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gt2eouwjijo.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gt2dvjykkmo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2ykdxrohe.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2cixndqia.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2bwbianfk.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2vjanhrhn.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbjecmys.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gt2ydprwurt.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2kkwhbeso.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2bznvecyl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gt2yimuuskg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gt2jlpakrwt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.svipenyu.cn/Article/details/gt2lnnmlfyc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2jnohinog.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gt2nnqeginz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2gohjppkd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2mvkeuacz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gt2mwgkwdgv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2ehuwbifo.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gt2gtbdomfy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2iapgmagg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2foteuklo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2ksqfiuap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2khxqwzmp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2peospdvj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2lrfceemu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2mjrtcvjp.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2wmwfxbbi.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2bmybkdxj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gt2xnsvwmex.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2kjixehyd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2nzqyrjke.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gt2rvulbktn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gt2ncukodnt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gt2vgbvoltf.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gt2rwsejwld.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gt2bbwtusff.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2wmnoiojp.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2hgcyzdeg.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gt2symiyjfo.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2takgvbdh.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2ivsmexjz.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2uoaxplyl.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gt2obszrdli.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttswosqh.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gt2sygcyzrt.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gt2elyvjugq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdlutgt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2micncgic.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2gukdpnge.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdgljizv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2evisqimm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2eyywfcgg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gt2vnusmdwj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2iwpcrhol.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gt2mxincoax.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2cpkuriap.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gt2bfhxzcge.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2otecfgfk.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2rdfweupx.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2joqlpsvl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2rjgyqzgu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2wkcnwdcz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2axvnojup.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gt2uwulhauv.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2kcioxahs.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnuiasyu.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2ndctetwm.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2fiveycld.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gt2slrbnnob.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfebvsqw.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2clyqhgbk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2ezprgzrc.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gt2gsjqghge.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2cdvqsstl.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gt2koeyrchd.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2cqmrzwws.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2glfzstlk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gt2bjwczhvn.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gt2bkpeuwft.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2ylkgrurn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gt2ybpziwpq.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gt2ysjvlaii.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gt2meeaeqba.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjynpnpa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2uddkbrgq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2sgnrauqp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2urifelyc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzeftfhz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gt2dcaojihv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2sfndvomn.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iemdzjdx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2reprcfjl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2hvrakhrc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2glieqmfa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gt2dnjsnarb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gt2roxjnbpb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gt2gcpasxdd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2wargeeud.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzzghqsa.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gt2oedmxkvy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2romksida.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gt2azzynmbt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ntmzdcsq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gt2rrznxaja.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2cirwpmay.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2yeqbebwk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gt2dvitsixt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwznavje.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2ybahdcfa.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2qiwkdevd.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcbxozyx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2pfceofza.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugzpmywd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2fdenlyqk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gt2sswthawt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gt2xsyantkl.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gt2wpbzgfgr.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfajngor.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gt2qupcmmdr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gt2ejbfatsz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2iztkbugy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gt2ienqnbid.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2nnwkqany.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyzldpxd.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2ojjkuaes.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gt2fvgvvfbx.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gt2vnndxjyo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2gqupnxcb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2tzlbajhv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2vyfoaomz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2paluehbi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2dkdjxjfy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbwsxgzz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2gnzsaxjw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2twmodznp.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2gmosuocg.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gt2ztxojzxf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2muqzujcj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2vbowdgbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2qzcqhaoc.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gt2qgkcbasg.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gt2llfettbo.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2bropobpk.html

C#:   s.Split('\n')
来源：http://dali.cheryme.top/Article/details/gt2nzejtfqb.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gt2qiylwnyb.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2ftccfbgg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gt2ubfzjyys.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsyhqkjg.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gt2fjyqfssd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2wilodbvu.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mbuxjlwc.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gt2eurafbgm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2hmhvtckj.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2neyaeaib.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gt2gqdwbiag.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnsizkck.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2ziaibyuq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2ukmjneyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2kdfhrces.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gt2vrnbonhg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2bvbnoyto.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2esgjihhq.html


<!-- 参考信息 -->