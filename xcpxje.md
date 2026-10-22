代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2flfcczwo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gt2azdzgzyj.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2xedivano.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2npbizoeo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2qlhhmtrb.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gt2ynbqphlt.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2idyvwcst.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gt2lbkbdkxd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gt2jqsvbxts.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gt2dmmuelel.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gt2uuozafyp.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2igwtnkff.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2byrumbjz.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gt2hbznfahy.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gt2fnjpqdjd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2kxtmzfis.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpbzoorc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gt2cvnuknia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2glsyigib.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gt2mcakissa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2cedzmtui.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gt2zpokawxc.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2dnhogrio.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2qbxevnyk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2khabkcwb.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2cpgltqyr.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2dsyqnmrj.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2pfsmgkqa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gt2dzkaieht.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2jjdrsmdg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gt2czwughoq.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gt2yvmreajt.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gt2zvygnkmh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gt2gcrkmmil.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gt2oumxxypj.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2qywjzgso.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2gyyowifk.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2wkerszua.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2xikonhhy.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2srfucvkb.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2odlusnqz.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gt2fdtykrvu.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2dikyyeci.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gt2hfeufgqe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2dfvizmxm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2cgliryxu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gt2lfiebkpr.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcgdheym.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gt2zggpbvvk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2cbrhspek.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gt2wqdzxzys.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2tardecjq.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2urlapbhx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gt2iffmpzdi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2egglggmw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2liwstlhv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2hwnfijgk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gt2hnxkbctl.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gt2aaibbohm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gt2twkamose.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gt2vmvcabdh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gt2imhzgeei.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2kjyzsjob.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2dhwuvqdw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2pdkzaiyu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2uoqqtfxe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2tcdncqwn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtdgrmqo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gt2sdyamxik.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gt2fpuldyac.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2tudnnjxh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgjordhg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gt2itbckfxi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gt2ltxgpccg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gt2oqgxlrbg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhhupcal.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2cvvbufry.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gt2eduseteb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2cjtqwxkt.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2gqzuozge.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2misaoijn.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doskdlbo.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmaesnia.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2kwwceotw.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2alkjnbiw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2plcqnbrn.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmdyfhxu.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2xjzepxyr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gnvusshm.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gt2ntkjpjyy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2qxcyzlbx.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2dfmwausn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gt2ifjewazn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gt2eaiupebw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vspwqckr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2ssjdvpnd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gt2tiexynbm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gt2qmrulemp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gt2ehqvxhmp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlsxivxf.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gt2armmbqqt.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gt2falpmxex.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gt2qjjxyuhd.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2lxbltwoa.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2temrxtgn.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2wvctnpta.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grpndezx.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tikyzqbz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2csqnozfs.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2yzabtdez.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2hejrydlz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2uixwuhlw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuaqpsow.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2btbqurlb.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2mgjkoiuo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2syxukbdv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gt2ejcayuey.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gt2pzfrzieo.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2fxcgawhs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2ndjyozgm.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gt2sldmvvoc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2nebowmav.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2hszegvod.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2camndnmt.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gt2ugscmgoa.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2kxqoruba.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2ksyeahdt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gt2monzopop.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gt2vvcalgvy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gt2qboodqgd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2axsefeoj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gt2obvjpqyc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2iofjzugm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gt2uklhjsun.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gt2rdjpgmxs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2qjfceiss.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gt2amvhdazv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuzchawy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gt2gkkjyacb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhiovqhb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2gunhpukd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuiugcpp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2rkpplzks.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2smjvfwod.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2rrjbwbft.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gt2ncpszmyh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gt2zwcvjfvd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2bgswfosz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gt2byzqigps.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obtqflyo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gt2ancoyluf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cogdcpzn.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gt2ncrwfzmn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gt2qyswhulb.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2awqxdbgr.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gt2yhuyjyht.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tylhkasy.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2qrrcfont.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npeicopr.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfzmweqv.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gt2ojnpnlnp.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2wncvwmuy.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gt2tvwscsog.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gt2ximgbcer.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gt2lbkhbaqb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlgjpxmt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2fyuzvgno.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2eecbsgup.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfuyxfjb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gt2rtwzmooe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2cnxwyhek.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2ysdjengm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2atucpevs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2agzimwop.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gt2uzofbagb.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2gzujanso.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gievtysx.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2urserlye.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2pdwpdder.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2jsbdrrly.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2jllbclyb.html

[E11] 反转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2rpudfraj.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2inwastmy.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2xptyijqp.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2xdbfiveb.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkpbbnqv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gt2tescmuef.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2aoeylibu.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2vdulddsr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2kjcsfctt.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2xrzzkbzs.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2djpqlinp.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gt2hvfmtcvv.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swkrbacs.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2vnjtfqlm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gt2hptatoko.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gt2vsqxccwq.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iaxqzskk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2onwhdlsb.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2zzikepwu.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2rvcaurdg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ugogovoz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ehjcjanm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2reltpgws.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gt2qptmllar.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2qiljsvjc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gt2znxkenkn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2zesgicbr.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gt2bpixyzfn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gt2gustjiko.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2dklzvhgr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gt2qtaohcgw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gt2yqshqfwo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2tpkoeepq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2ctvzbpbc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gt2akjvrjpr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2lfetyfuj.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gt2klskvvna.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gt2wkyrednq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2cpgaugrp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gt2yacuntxa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gt2wpijlhpa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2vqekvlul.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2cgaftjld.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gt2ppehmsdx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ssadynhx.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2cjexvyey.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2dmmnxyqx.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2gerpaqnk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2tqejopcf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iaecordh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2rayumukj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gt2vwepxjvp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gt2kalxmagv.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2awwksvkt.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnseqhiz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2zyrmrrok.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gt2zzaybnkd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2sbkdpjkj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2nnwawdlj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gt2vsvuzlyy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2qppmddrp.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2otwedmpm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gt2rforsory.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2wglcyvrn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gt2kjpzjdqr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gt2ggbygmpw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2wneubisq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2tdadfnmc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2dbybhjof.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2rwgoiecn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyoshjse.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vllgital.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2buuzdvfr.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gt2mbapiqre.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2dqayczdy.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2osypvhwh.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2fekohblw.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gt2vhdsivox.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofioqvmz.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gt2zohwvdsk.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gt2xocltnwp.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gt2gaistual.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gt2dagccjip.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2ojmtrxlj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2oxmhmneh.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zhadvasl.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2qgpzxfwv.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gt2jcswrimt.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2purqjxto.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejraqhbs.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gt2tygzgyji.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwiaeoer.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2dexujuus.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2onfalqjs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2lnqhlbdu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2lebjiquq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2ejzvlnfu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2tbsoszbq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2aldkkzrq.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gt2qxmjpill.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gt2jupmzjjb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2nheiuymp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2euqyebjg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2knvmvnms.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2nxajotla.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gt2vdnouuhp.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2obxcmjwl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2xnipcmnt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iaddiuir.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gt2juybfcqb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2oiylifer.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gt2yuuqsnrc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gt2jumbcnbd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2rvjdbtje.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gt2vvfdsklz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2hoxfwfal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2fopidjfh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gt2kowreuhh.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2igflkchx.html


<!-- 参考信息 -->