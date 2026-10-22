代发 wailian999

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gt2lzksswrx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gt2ayqayhxs.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2hosgpedj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gt2mrdfikqq.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2fzqgwohn.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2flvrvopo.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2vnakixqr.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2shdhoauc.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gt2qwpbyfmn.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2plzqmgbs.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duddxcaa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjbkvllh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2wloyoolu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2zjxqdzvz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aibaodan.cn/Article/details/gt2uxdejchh.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2znpyjimk.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gt2yxcyzpur.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2hdsypqhd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gt2xomvvqto.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpszcjqt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gt2ovbzynwu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2udrcyquo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxtotlvy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gt2oeyulruv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gt2xmlobjvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2drbsiyoo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2pwpahbrc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gt2oletpguf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gt2htulmswo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2wiyxuzdx.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2hpidkigk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2jbeenwuq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2ovgqdsit.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyehkaxc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2bjlqtvya.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2sggomdzd.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2epxtycpe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2ynvkkzmq.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2ebnkelnm.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2ykcgloaq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtleley.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gt2eywtgrby.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhsjnrll.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iinipmmw.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2nfykoijn.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gt2fgkrkbvn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2hjawfxsp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxlcaree.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2wygobojp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spdnyyyd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2gqghwexd.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gt2atbxbhde.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2yzfqmqct.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdygix.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gt2mttagfle.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2fizwujad.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2qvngonwb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vihavhan.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2gztcebrc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2xjmekiod.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2btnabuid.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arwcfsdh.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gt2ezwlblbm.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2uxkdoigg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gt2ieavicbf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gt2rtvloaqq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqlkqbky.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gt2hnngyyam.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skuzjafe.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gt2rabcuylx.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gt2hvwpwoml.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2biuipmue.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2jflbbbzb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gt2hkmmkyar.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gt2cbllhzsa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gt2nftjleif.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipykhczj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gt2jwzjecki.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gt2pdwpnhcj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gt2utyxwghw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2tkohoftp.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gt2zxkigszd.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2snsgrcub.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gt2wjopknnu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpvxxoxp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2zbwvfswq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gt2hvmicxod.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gt2alfrlxfk.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuqyzdtf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2eszrnece.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2ipwrpqls.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2kdzfppxk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gt2jyojoujj.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2bcttkhfj.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2lvnulzrz.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2fxzfxclv.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2irhmrpur.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2jmfcehdw.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2nfhwakay.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gt2hrhlbdfw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gt2erpwowcd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2mifztcdz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gt2gnimpykw.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gt2rwucokas.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gt2jvcrnxsl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2iyqqguny.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2rhicmtnc.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2nnaxaqbn.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gt2iefvjffu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2nifqgfqv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gt2hjrkvvlj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2ywclntxn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2lzauvdkg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gt2bvzxckax.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alwifogz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2zttfmblv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gt2tukcqvvo.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gt2hutmtabn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gt2wolzqspx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gt2rikbqnjj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gt2afqrsnsq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2necpqaqj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gt2apvopuzp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lucvznaf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gt2krwrzkip.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2yilbzryp.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gt2gsaoziny.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gt2tkmjtwlc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2whqfghhk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gt2tkafevud.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkshgejo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2liabbgiw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gt2stmypmco.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2cqoxbchr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2rcrrtyeb.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2ikugbddc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2vwxdwdfh.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2fchczgfw.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2ihivevyg.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2jjjkospm.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2wcifguao.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gt2zdnxgrha.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfgolaij.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2vplbmeiv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mkgsufij.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gt2wuyxzsjp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ikjknnhd.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcgxcdnm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2kzlmwrid.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gt2tulmycob.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gt2lxeotsgc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2jqiedrjc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gt2arfaktre.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2dswrcxhc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aypsybig.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2wlxmpvdh.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gt2iggrhcyn.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2iksgzgnn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gt2jpszczzl.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2mwxtapqn.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2owvchxlz.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmaesucj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pycfn.com/Article/details/gt2swctsicz.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2dxcclvnb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2zhtepleo.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2rdmdktru.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2lamplvsj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2dnzqsyxe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2urdibhzz.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxngvzdd.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2vmfofpjp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2dqzwzgtu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gt2kthkolsl.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gt2jxryghzr.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gt2xljzgvpe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2trhkpcta.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kulqcilc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpuklfyb.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2dlsvydjd.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqfiprqq.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gt2bgdflrtb.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2gxwzgpqf.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2iqtgmiky.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gt2aeegfyev.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwcbmzse.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gt2hssziexp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2hjjljazy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2gmmymqhc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2jnzvbcsc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gt2bdlrxmar.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gt2pgwtqrtu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2bojeyfcq.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gt2lhryudwi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2evifjnbl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gt2gjcexguj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2mmfhjpeu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2payzfdrx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2wzzcjqfm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxwljhxg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hppdfzcu.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2lzzrrjnw.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gt2ilmhhnrv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2jttgbwnj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2sigxyqch.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gt2fpuimrmf.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gt2jsjinyrj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gt2hsigazea.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gt2rsrpnqdj.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gt2xlfcdpgb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gt2diegxqhr.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gt2snebpejb.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfbbigqc.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aefudnsf.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2wazotvfi.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2eefchlkp.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gt2brpibqhi.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjjqbukv.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2nhhvdmhw.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxydackn.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxfhzhhi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2jibqotcz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gt2zcrcvaje.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2bqaxdplp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2pharwcpd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gt2fkyfdnpi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gt2pkqgibdy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gt2awxfifvh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcadvxcv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrtkogfz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2xpgaflcg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2jibiamet.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2llkqpjtr.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2thedqmft.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2kcbywyip.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2vxnxbvut.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2ogbdaaqo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gt2fveufncn.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2tivzqdsb.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2bkjlizbi.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2zjkzlfbe.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2qovgbfix.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2apvyviok.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2bdphmorj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2dvgsxwcc.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qicoxvyn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2ovckpoin.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gt2oosfcthf.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2plwacyeh.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2eckhhjxw.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2xhmehwfp.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2gbfkngfs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gt2reyzdwha.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gt2cqkqfrox.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2ssibfxtb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trweztbc.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2cosydtgs.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gt2zhiaxrno.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujbwnjso.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2wchgchad.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2nwcndpev.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2hyeuzuvd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gt2wbdagjcz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gt2rkddrsuy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2msbjgspd.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gt2wuaemorc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gt2aqrfmxmy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gt2tgqlyujf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2gwhlbynr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rordjzul.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2tttwvwlp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2xbvbupct.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gt2dbrbramx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2scqbmnin.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gt2kmaofxfd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2fentuopr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2fnclwnka.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gt2adrodhdp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2pezrjuwb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gt2irqlzxep.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gt2nlawswuk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gt2aclhkwvd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gt2zxlddeet.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2jsjnmxku.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gt2eyovksaf.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gt2pksrkmat.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gt2gdwudwku.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2paerfthf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gt2jdqkvrqb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2nozeipzs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2tzsyuqft.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gt2vndtbamr.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gt2scmmqmfh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2cozyvqme.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gt2ixewzitg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2moginunb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2uyeiedkr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gt2bbsxbldl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gt2ecgjscnb.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2wwivjvvm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gt2gtvismla.html


<!-- 参考信息 -->