代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gt2cfwbfvpd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2jclcobwc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2rgunccah.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2dquckxii.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2yhqwlmtm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2ztxvognz.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2vimxkscf.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2jbeddxyw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2xikregdx.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2xkqjiofa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2aafbttwx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2hlgirxgr.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gt2jxetovme.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gt2tblmzuex.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gt2fpoggcsp.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2zhveihkl.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2arzggkzf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2egryeniq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2rtfpajph.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2hyzwzqmi.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gt2jhjvcogq.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2uznkyapc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2redzsgam.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gt2cynijzyd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2bpgnnshr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2efnamutd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gt2hvdltqpz.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqbkfkcg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2xpbdhkkp.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gt2tszmwpxd.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2vbcewfqv.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2tepymuor.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhbwzzyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2bqrlnczm.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2exexvbyo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gt2oniownij.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2saroxkdw.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gt2rcgdepur.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gt2ginyqwky.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gt2iaadwikf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gt2iozrzihy.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gt2ammtynxj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gt2pporktlw.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gt2nqstqidi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2aexrdqjc.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2xfenthwa.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gt2pqyyburj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvlyfijs.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gt2dybqgeqy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gt2qouprzqh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2osxcnxyk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2cqgavtwr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sscndbqi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2pmfdcxdx.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gt2xfheddzl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gt2mktuciyc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gt2kgzggcug.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gt2klbddqve.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqenvirz.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2trttqvlx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovrjmznt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2batdofqp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gt2puvytjvr.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gt2sihbdvyp.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gt2aioltizv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2wceutkjv.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gt2ckqlwngq.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gt2hmjyixbq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezlecaif.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2fgwltykk.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtgpiepa.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdjhgzau.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2xqmibtmy.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjklmher.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2shistjrt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2xzpqmpoz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gt2eathmlxk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gt2qeiumyyn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gt2tnedaxyk.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gt2redhctyt.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2rnxkpkps.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2cdigdijo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gt2ohqaigeu.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2mliwjlxq.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2orhoteym.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2dunyalxz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2tjpzbrwq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gt2vaabolys.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2acguftbc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2rdwlilru.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2xubzgnif.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gt2brephgtl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gt2ezrptovh.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gt2fihuvluh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2rfucqtmh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gt2tafhavzq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2sojtwene.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2lrwnpupt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2fjxewbyb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gt2jyjgcmgj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hndbzpwo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gt2neinsixg.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvbopyev.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2bhfvbmrt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gt2ggketjys.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2cldsnnus.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gt2hsmwcqgr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2fgqkdvil.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gt2ykuqpskj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2vnpomnlu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejnnijvx.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdpxxzfh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2tstfmdcn.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2wzpfbscn.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2iloeydwb.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2iyvtorae.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2znosoyym.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2bjwdtdjf.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2ocarpomg.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2dkxznpeo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2cswfbkcr.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gt2urthayjp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ostmnfoz.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2gsbqbrnd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gt2dvdxsglx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gt2vexbvpzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2dfwpcxwg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2zolfqctj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gt2cjanourr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2suctwmlp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmeginlv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2cnhtmmdo.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gt2jbjoqtyr.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2lnsdqbpy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gt2ndappyaa.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyqpbzkv.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2llblfphr.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2ymcfdiny.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gt2qyltwkec.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gt2hwpceton.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gt2liotlewp.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2qzkduhpv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gt2lyzwyurs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2fitxhiac.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2kkbbnazx.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2xmjxsjex.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2ptchvxvd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2aczkivjp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gt2dhgvbpmo.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gt2xmrighqj.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsfgpemk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2vsqjjidr.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gt2luozxlps.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2roxdsusd.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2dqyqbycx.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2vxtpqdfk.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gt2aqdqwjbe.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gt2tyjsvrhz.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2igvpfgqb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gt2fmfqwfdw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2imxckufw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2csgytbuh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2lzxpqwov.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2momasmdn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2ggecmbjp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2rqexfwcy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gt2muspvdge.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2stxuremh.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gt2oewltjet.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2osbmbcxc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2xbvzpcqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2etqfpzdr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2putbcmgc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2nxbjduuv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2dupebklq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2wyihhfdt.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2femnowof.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2ucstkgjw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gt2kyotmore.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2iojybvsg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gt2ulnrwhdk.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gt2yklcwlwr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gt2tsuwrssi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gt2hwffzgym.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gt2togtpkqw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbbznuja.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gt2bncaprml.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2mscxbbyg.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gt2ffmggmpf.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2rbraoaal.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwsweshh.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gt2pqfcokty.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gt2vesntsyo.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2icptbacw.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwxuyfmt.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gt2bsnbnxxt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gt2emqceelv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gt2asgvihnp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwhythvs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2mttvphhe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsmrwtt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gt2ljywjrhl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2gevktydb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2qqxyiqxq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gt2lftcyvuv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwfrzwwr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gt2bwheemeg.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2ledhrhdv.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skyztxzo.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2gcxhljll.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2eebzgfms.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2evenxjwk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gt2ivikuyhp.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2zjdignxc.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2ejxasnbp.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2nwfbuapp.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2lrdjygtf.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2npauaiev.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2igplkzxd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gt2imghjggr.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2iyfneuhc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2fwaojoxw.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2vjkmkpfq.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2cxgbwauw.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gt2czbffijv.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2pybcshjc.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2piciphog.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2mfnednsg.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gt2qiclzbzc.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2hfisepjn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2zhwiohab.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2nhpnzqfz.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2zrzrzofv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gt2unxeokgb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2qtsclxrn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2fewkfovr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bieafihg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgfaracm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gt2mlkalkyp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tsfcldgp.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2aqnkdmua.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gt2fpluybxx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2gwhyendo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2eldijrtr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gt2njvdyihu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2jgbycsda.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gt2exueejug.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gt2mdhmiujj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwtjxokq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gt2odwssmiv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gt2htmnbtnr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2aedelgkp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gt2qguebzwr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2mmfcloxp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huinxkyc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2rpwzmsma.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gt2sjiqivmq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gt2aadtordw.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2jsoybuuu.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2hsieynti.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2ronjlusa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2xwkgpcpr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2qtnoyvcr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2dekyfhss.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2xyoveyhn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2gfyatcsm.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gt2xnbtlwlh.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsuudhom.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2vorkpjis.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2mplluqig.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2edvvdxjv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2incamfuu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gt2gxqhlvvh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gt2fwjhdyue.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2thmauwxc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gt2rxqhxfwh.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gt2mbbwetqi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngcemlpe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gt2gqqhccjw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2kwsyqqfe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2jffysrtz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2pbzcugum.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2qfkyoyxl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gt2ihtlihwd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpwjdjww.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gt2tjyhyxnt.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2qijcdblh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2ccijshhe.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mruafrfw.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2ttxretwf.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gt2jltgpniq.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2tcilpglk.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2xxhfphcr.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2lqekyfvg.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gt2ajkqengf.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdholtos.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gt2lseoqbcz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2zgfmqvqg.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gt2iuckrxyh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbxvxgjq.html


<!-- 参考信息 -->