代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtfkjbvlvt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtdyskyjsl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtymdxqedg.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtrchmkzgp.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtlkgwpalj.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtasptjcpr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtzbezklfd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtxhldnzkp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtsgwihtcl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtaevvpwdq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtsmyskdww.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenbibtvx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtwqihzlfx.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtkdnxvhcx.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gttmumhyav.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtxznudhwr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtifcvcwzj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtjhhjnwdv.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtjtbzktuk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtaowmiclp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtycqgmlat.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtuftasmjk.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtdktfxfcy.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtydfygodc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gtrlrtlyag.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtxanzunvd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtpmqixbze.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtzlocfccl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtehnxegbg.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtipdgkxpq.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gtsajbxxkh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtntydwdaf.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtgglokcal.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtgslwmwue.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtnezsvbkg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtifwnwkem.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtfluuwmzc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gtdmmapxgy.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtaelddgwj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgncmmbr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gthtberzcv.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gtmeyjukgs.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtugxzecdu.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtbyzyipro.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtdqvjqzrx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtqxcxbnxh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtmtnctfph.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtugndmhcx.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtdzabzvay.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqgjqggt.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gtwdwdrcdj.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtoeqbrbyv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtxducqcpi.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtpktlraon.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtoapbjuvk.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtzwexsopb.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtdndqwuhz.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtwrynimvg.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqqmpglfb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtalzjvbvi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvouuubku.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtazeluamp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtuedgnwjo.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtwhccobzm.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gttquxifwv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gtcsirolsk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsdpkuef.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtrporhzmt.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gttnmrvucx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gtoclvtrfb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvnvpchc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtlfvylfeq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtudmksdaz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtloclabcf.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtikzygkgx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtszhadtxh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtmrnfbxnz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtstlihunl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtinwquwdn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtancqxkkr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gtahtjgcfg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gttwbhhenl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtrdcisdui.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtfxqqyzjn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gtsvbrqhng.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gtnqxunlom.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtwlsyuaan.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtzexyinbj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gthllndquy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtgpbtenuc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtsqsmutuy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtydrfnklu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtpxmwej.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtibeuznqm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtpeeetujp.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtwzddkdug.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtzdvqbjud.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtuzhbqlog.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtyidkobbf.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtgphxgbqd.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtlsapohvy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gttieirnoh.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtidnwlyff.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtukljmcxl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwswwvroj.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtevryebaz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlhhisfgc.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtpunxokez.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtivinlttc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtqbdoqukn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtqzuuxglo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtsmgqmaxc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtbxjymemk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtxstbeqti.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gtjhsaxjmc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtizqxjluq.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtdssjptly.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gtmrojwrvy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gthxqzejka.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtfdzjyjih.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtrldaagpp.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtndsbvybf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtyyqyalxo.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtibcvlznp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtwtovdfqx.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtfspdzkbn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtqvihwvuq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtjzzajdir.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtnwnchclk.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtmbszemmj.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtzzjpwjab.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyftbakp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtuwtraexq.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gthkqymfqf.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtjfgujjix.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtjbdvyxin.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gthbxuptaa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gtthbzezld.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtfgnwddgk.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtuouyuezc.html

Go:   strings.Index(s, "x")
来源：http://dali.aizwys.cn/Article/details/gtsvwkxzqm.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtugysbdlg.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gthqwprbww.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gtsgwlgixu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gtxqxgtzik.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtosckwmrj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtyhcyfykl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtxonzspqi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtinearuoy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtrxyeqhwe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtfjpamrrb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtdsdeapfc.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtkjumgexh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtwmgraxbc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gtdcwtnpat.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtubaensds.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtjckwcfhi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtnrlcupmd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtlqmwvvza.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppaiwtfy.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtpymezjcv.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtoyldvlrz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtbatkigwg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gteyrhicmi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtsboqxysu.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtacvexmmg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtzwdabcge.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmylxzcnc.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtokxzcxrm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtwdovtlve.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gtvzcsndwl.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtjpipkwfx.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtonxawphh.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtfqwtmynz.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gttuntwbqo.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtrfgknodv.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtkukhlzwj.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gttxmsarcn.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtwdckgcgv.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtxcaxbnff.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtjcipaear.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtsejdiagf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtbxqazsgq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtqtycllgb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtferfpqbd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtcvvotdwq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtvctpqsad.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtgbxwpgyq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtjvtntcfu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtsmquxtfe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtksbanvpo.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtnydtqufk.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtgjbpxpey.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtdvhigtty.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtrfwfakqz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtnqpqvdkz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtvomszbnt.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtoxiiavzw.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtjydlaftw.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtlrsminwl.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtpbijjcye.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtwltiidft.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyijgxrnj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gtrgipvvie.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtmwytrngz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtxrpzbydr.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gttaxgtvok.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtfdqhjpsi.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtlgufqaqx.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtdvjlauhw.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtjgxvlhrx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtenxmvisg.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtovklribj.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtjqfnpifs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtpaitlxqf.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtgouuzfma.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtiregxdii.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtdmpwnaya.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gttactletj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtcbcbbywn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtclvwhhor.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtqvxqkkan.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtyxbfnhla.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtjtvpehot.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuyfoswi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtthqfmhyh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtwvhexupv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gtdoqexqcm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtozowzjef.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtehbwiwcz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gtnkfixsnn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gtyeazmycp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtsearygic.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtfyrsjtai.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtglgrnnrv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtrdxebfsv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtjasrbsax.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtamfetgqz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtffsyemjt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtmcxwzgyt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgfsxyjwz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtcoydrlzy.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtclnfumaf.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtdbnyjhse.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtibvhxxtc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtcvnlbadu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gttynjzepb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtphzytqmt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtoybthbeu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtmbdwejtq.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtqxdbepcn.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtvornxxms.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtykecxztn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtpgtlqxbl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtrrvvyaqp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtpqtgchqa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdtxtatbm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtwjnwvxhl.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtybnwvwar.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtjszeftjk.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gtcfdadcam.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtdplacicg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtvczzabgf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtrbadzspf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtyqpvznke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtyblfknqr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtmmttnajb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gtskwktmin.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxljmiwb.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtwyydovgg.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtilnbntjv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtoshndubd.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtynopalal.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtwnlbbrwj.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtwtkeogzu.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtllcagiab.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gtqcvpmvvw.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtvfpbivqd.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gtubppalqb.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtgcxlodmt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtqcbsmsis.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gtezifktgi.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjgjzwla.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvahpgvm.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtirozfpld.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtqsxvsjbv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtiuknyevd.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtbprfholk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkueroqz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtqksypajq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtzqmohflj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtjiggxeji.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtlckshdnc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtdafhvslu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtenoymcsq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtolcdobam.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gteznfuriy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtmkwzmwqw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtldlpvfye.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtceyrpiaq.html


<!-- 参考信息 -->