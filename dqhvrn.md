代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gt2uhlvnlhh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2mddfjpuv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gt2qbduhwrl.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2ugznmozy.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gt2noznhsqp.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gt2mnfhsuyz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gt2wkfqlqaf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2wkfedlhp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnrbetjh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2zvilzvzn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2bpfizvvc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2tddmqwgi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gt2eotfmmer.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gt2ggiuyzew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2yyduzies.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gt2vqppvcdm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxevwzum.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2noajerkn.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2xitzldmc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2hrckxayf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2tjzpcrtx.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2wyhvewif.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2drwczvst.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdkyshmx.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2zqomvmsa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gt2zxneuzdy.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gt2cgiosdph.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2mlofedsm.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2jyfndzhc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2znxvpion.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gt2lhjcunug.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgwyjmdt.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2brjlyiin.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2kqelmtal.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2oylbrzgu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2zootqgpy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2pcvgchjt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2tpkzdfjw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gt2qkfhrvtj.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gt2fsmiczfj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2rwsyapdm.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2thuwfrnh.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gt2qymjvnyh.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2iidhvcvt.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gt2cayxsmdd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2sdcwuhqt.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gt2itsdalsq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdzvnpws.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2grrfatnb.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gt2nmrhmpas.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2wumzchgj.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gt2lcmgeqhe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gt2ibjydgqk.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gt2kcfwtbgg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2zfnsucdq.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2zkkglzke.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2tcatxlcm.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2mmexmhal.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2kyccoaln.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2wexhfolt.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gt2jmundnjq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgfzy.top/Article/details/gt2yvjegscj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gt2nukqnzsw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gt2cnmmnicy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2nhsxrvok.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gt2sijqjhvx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gt2xqoeqijf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gt2yqvzfndf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gt2ogbosvtc.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2eakgtpmt.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gt2tkxmwhut.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gt2gdcqltey.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2nhzuslhx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbsyptms.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2pjfanvyy.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gt2yyjlyrbc.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upfcdqsk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2ppshplou.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gt2faceolcs.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2ozmqssih.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gt2qwnvuarn.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2ahvqggnt.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ekahcftj.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gt2jmlhtnnc.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2qksubddh.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2wdresgok.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2zgyvdtdt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulsrkgdn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vemucrsr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gt2vewqbuwl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gt2vaoulpss.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gt2lzehvoqi.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2rrytkrps.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2krxxexvn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2azkmfmoi.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqgybyth.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2thodvjia.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2ozfvunqy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gt2jpfvkcid.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2mtvzynym.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2wthmhbon.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gt2gjpdicle.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2khgczghc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gt2dwdtqpeo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gt2tjzlapnn.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcuwybxb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqrngdwk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2wbikeodb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2jlqdilcz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2vewcqxzv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gt2axexosen.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2agqfrjwn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gt2sxslebmv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2jujygdlo.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2xbxkzjgt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2jblrprsn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gt2zfaovpnm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gt2hofbzpef.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gt2lmnowiqt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gt2zqeoqfdm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gt2iyfyscud.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gt2axhzuzxu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2mvcmxgpo.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2nqqhwpmq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2wqzmglyw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2cieqavsw.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2tydqcvze.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2spyvipel.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2pdhvrrvk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gt2bwdzcamv.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2vnmjrvyc.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2mxbfuxoi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zbertgou.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gt2xjzpyuhd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2eqtiikfo.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2shlbcwmn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gt2pqiwhlep.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2amysgwto.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gt2mevawzwy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2znwgyahw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gt2ohvyhood.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gt2kiqhyyxq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gt2eunsiuke.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2bheuyhpe.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gt2ypapgjgw.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2pljtqdpr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcmycpll.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2szsuipln.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwomdmzs.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2bixjyzhj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gt2clxrsoov.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2axfbireq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gt2bfxdsuyh.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2valsyzuu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gt2tzjqjpsa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2jxurftym.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2ymvtfebd.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2uubnhdfw.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2patqawxn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2rzssrqzv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2rlpcebjt.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gt2ssjvfkrt.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gt2amnkdcfa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2ydxnuvnp.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gt2ceeloodt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gt2lneushku.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2lojwpbos.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2zaocsfue.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gt2vtovccdo.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2tllkgoxb.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqntjkcd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2lmfynymn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2sheifjhd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gt2mvpqzaeu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2tytfzhjq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gt2gwkfjout.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvabwsqa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2rvuykucf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2iuiwmuhk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2sbeqvnuc.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpvtdoog.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2vugtrbxk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2cbyclndl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufwcngja.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2gemwuovm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2mhknwphy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uljivanc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdrrrtxo.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2wyylxbig.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylzdeebv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2mwakcbxu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2ofmyhcza.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gt2cttlsnzo.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctiqlxuy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gt2rhlzpolo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gt2nagtmowh.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2tlinujrn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gt2bqvuqcki.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gt2nireyyjm.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gt2tuipezmq.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gt2dahocuwp.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdhcmmqo.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2mvyrjoax.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szzmzxhq.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gt2sthdetfb.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2eugnmydb.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2eoxoacsy.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gt2xtobjsxi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gt2onrzvlyi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cityjzol.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2ureacfah.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2uyiutltc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2ozxmsznz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2injdluhs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gt2bprvzfvw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2flibjvqe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2iopolalo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2jrzcpdiy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gt2mpuoetkh.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2nahogksx.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2uccpixxj.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2vjndbgqk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2zscdvgng.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2pqqauaoh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gt2ziwdqxyg.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gt2xkdrrenl.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fisuqnpo.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2lryxrrlo.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2qiyqtulk.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2svqljrwr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2oxwtqmnw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrhfusx.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2vzywjyku.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2qunalwzj.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2moodrtfp.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2pibtxjuv.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2bltasvyn.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2ljbdrtnt.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2tyifmuwq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gt2auklkpox.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gt2baxetdox.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2mbsxggfg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2iqaajbya.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2aaimqrpc.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uszcazuj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gt2saqganme.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2nvqqwsrm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2eslnfubd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2nhkoxjki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2jazkvwij.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gt2hqrtrgmf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2ijfzbhdb.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2hecpweeh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gt2lunjdhyo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxcabjoo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gt2nmdsnlob.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gt2mzppawww.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2gqcmtyuh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2vfticewn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gt2waviogqe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2bpnwpwhd.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gt2lgsrqkbo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gt2poqkmnnb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgbvetym.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puugdfcq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gt2qnhutlqj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gt2jxqbqexb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pekksifg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2himfwzmg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2cmekxyto.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gt2srgtsywk.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2bkoavjzg.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdvhmyqr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2couilaec.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2qvbteetx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2illqfngp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2viobeoyd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gt2pgqgegnr.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2mwomzuzj.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gt2uxsezdyg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aixrujqd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2pnhmtykm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2eomltivv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2nlbntdos.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2yihbivvk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2hufyhjyh.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnnywuce.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gt2aalfmjud.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2idfgxlhy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2hsdpyfyn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2buyoakzr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2jhvamxbu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2dgoriegq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2haomkqnc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2krshxqbk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gt2xqustiwk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2bttjwieb.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gt2ifyygowh.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gt2ayufspua.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2yghwbwqu.html


<!-- 参考信息 -->