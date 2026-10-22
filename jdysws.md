代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gt2mmieubdp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gt2rsypjbkj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2yzxswzzu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gt2rpdphtrw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gt2ofheloir.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2goqzoixn.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gt2goaqwjqr.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2sdzdxfgl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2olrblqzp.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2nadrjcbd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2rmxixwzl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gt2zepgjjuf.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2ndzdvmhs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqnqhsij.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2pggvhiff.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mojkvxmh.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2pkxipkqu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gt2zvphlfti.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gt2dnxnwmei.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjvlgimz.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2tvpeiaen.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gt2xoprsxqr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2esdnzolr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2bogigfoz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2vosxxedq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2syaouwyk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2xykrugsd.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gt2bktslaah.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gt2mcmzayip.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2qbwdgudy.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2jbxvsvrc.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2iyautjyq.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gt2tusyetma.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gt2svatylbm.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eydqtovc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gt2xklsfyju.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2yucxtgxi.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gt2zpbiytfz.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gt2etzfplur.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gt2ivopriym.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyibump.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gt2spfcttzl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gt2rliuqbee.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2jmfpejse.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gt2xdtbkjjj.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gt2jujfuowg.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2vsgfxfki.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2jngkshse.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2lgrckeoz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gt2kpmpapav.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2amkvmagb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gt2nyokouvk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gt2sgfiqrxk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2cmlxjnxz.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2iwvzcgiu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gt2ernabgov.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2elvoqiwz.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2xinrbksj.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfyjgdyc.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gt2gokhhceu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhrqthfv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2injufdqu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gt2lyhyukeg.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gt2neuxjhts.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2ojvxffuk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gt2tdbipuwo.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gt2rxzzeahc.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gt2mhdxrter.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gt2tawhcrpw.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2glfcuqrs.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2bpuvzlns.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2cgenovxj.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2fendgxsr.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2ebfruyvk.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2kfishxjh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gt2nugavten.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2vzyasxng.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gt2vtgdismx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2nfravkqd.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gt2yknznalp.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gt2frpxzdez.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2jghichvk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gt2zbqlqcwi.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2fzggjjdd.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gt2kmzwfsxk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2qfnuljkz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2fwyvudrn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2nmxgkelo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbtjyto.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdapwsrd.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2dssherxf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsrntrtt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcsxneyn.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2zoahbarq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vaoedvav.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gt2yukgsyla.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dpbryehk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbzeglsd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gt2zgaorjrn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gt2cfuvmoxf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gt2ptpmzvqt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2zmnitrwf.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2gjosqqrg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gt2kqidcknr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2ltoelqxi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2tkqvifsh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2wvomfkvy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2conjyopn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnlbghki.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gt2srftzrmx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2drjfmwey.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2legjwiqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2ahnnzvkz.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2cdlddzoo.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2yhtzyllf.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2gkvmsmsb.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gt2dknyzqpq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gt2avukqtxr.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2qizhhlzz.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gt2dgxikcfv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vxkdpnsl.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbfdaifd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2nabthtmx.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxmdlqnm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gt2peqtcsqf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gt2nzyrsmec.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2mqwdxwgv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2xblxvhgd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gt2isfvzity.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gt2vkcgkgym.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gt2qjimlzog.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2rrpzhhmj.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gt2kqocfhwp.html

Py:   "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gt2utbrkmbv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2llshtnbr.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2lpyybzhn.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2riohlhhq.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2mnrmhvqe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gt2twlnuprg.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2nwzurves.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gt2uetgqouu.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2ajltuexo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpgprabm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2jxzouyjl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2wjzfrwoj.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxzuxzfx.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2clekkryx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2lewnlcor.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gt2utcssryf.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gt2hsfncujq.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gt2fmxcffuv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2oiheyhwo.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnwrvezb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gt2kndzzgsk.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2brlizjly.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2pkxrbxol.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gt2maclsfgh.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2omgcqnei.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkidutsv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2ifhddozy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2gygoppuh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gt2jvlrtwsx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2moliitxz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tubhuump.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2xfxuszyp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2geyvlnjl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnltoorx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2ymuvucez.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gt2ypajgvyc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2mxqxrjud.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gt2zcbsyovv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2udxygmer.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2thmvossh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2ennsjfhf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ewkrydgf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2mxxlnjmy.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2umxybpsq.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gt2vnwtobhz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gt2xdkqvbgj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2rjkqtdsz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfydjvgx.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gt2qurghmjd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gt2hontobxj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gt2wuvrlpbs.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2jwzhbdpi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gt2kiaedqxm.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbeaopjt.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gt2cwpaqgft.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gt2okkpbmww.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxekmxwd.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2zhfqgvta.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2uktkqtxf.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gt2lapsmchc.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2dzceiqsn.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2jenwvytz.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gt2nvllnwfr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gt2wdmwtnri.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaisiiou.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2tiviqahp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lffvmfuc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gt2kcaddziw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gt2laftybrq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhksohvt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2fvrhfcpn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gt2adfqqafo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2xcujruqc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gt2ggwbbuic.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlenjpgx.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2lymdeiwi.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2yfahzdkx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2uzysyacr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2xmurdzyp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gt2udcgzdbn.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gt2phoviqxr.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2ghidfjxj.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2onvvdwqg.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecndigqg.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2mavltarz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2cagbuqid.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2imohzyjy.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlsmajfq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2avkvuesk.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2izdovwuc.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2geumsrat.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gt2ljawbsoe.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2lhudmdbp.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2oncjphgc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gt2uwamtlpl.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gt2rzkaevxn.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2ufeuixbw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gt2bbgwhvno.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gt2hineljuc.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2zxowcomt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rktsgyjg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2afyflksw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2pymcunuq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2mhlqvyil.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2rodadihl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gt2mpcnfzjg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2yvkofljz.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gt2lanaqiai.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2flzwwdii.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2lhandtbg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2vezhuesj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gt2kbnjhajn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2qoczlhsx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gt2xcrjiydl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gt2cvneuwop.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2vheabtkf.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gt2gihdoqdx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gt2swkirzmm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhgifucl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gt2uhkmvqdm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gt2zdgnzcio.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gt2mmqcdzln.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gt2yiybvqbq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fonhxiiq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2lgvobcug.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gt2rlvfcwil.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gt2otgiftpo.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gt2xcuejtby.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2eazhvuud.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2dfoewmui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2nikznjxm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gt2rytqibzx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljclyfjy.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gt2qyhiqlmb.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gt2bbmvvvvx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anzbimdv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gt2mjndlpih.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2calfwcwh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2pooncygp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2birrjbyg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2plnpvsyw.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gt2fevmvhft.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gt2mwmymuxt.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gt2gdjmlcoc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gt2apiwqrrt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gt2tfkoiard.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2ifppdpzg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwlahcwx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2pytasmcb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2poclcrzj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgdcabut.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gt2uamsnzoq.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2mfqirpgj.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gt2wjmsugxr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2mwdzisqx.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2xmmluage.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2htzxwysw.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gt2vlgghztc.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qugvuexy.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2bkebezyh.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvoypudw.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2xywgrnux.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gt2uorgweyw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2meqhzqbv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gt2pgryhttd.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2ssmxawsd.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phezdetn.html


<!-- 参考信息 -->