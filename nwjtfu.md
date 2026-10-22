代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2tjayfndb.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gt2hbrcbqwo.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qarfzrkz.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2vnffquaa.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnirvcae.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gt2pihgchep.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gt2dbpjrjlk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gt2oxaefdje.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkbnfovc.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gt2uvkhslqv.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2otqfpdib.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzlwcxgf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gt2ypjadydv.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2jccndtws.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvjgbnxs.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2yuqkmppv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gt2lwtgzjbp.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2xkxllbsx.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gt2wltufqlx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2fsxasanp.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gt2rwbjioca.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdwyzngl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2oxxqahlg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufxoaduy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2trhgzmtc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gt2wdujckyf.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gt2chkjnbjk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdbxoiic.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gt2ojiisdao.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gt2lzeanhod.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgbwcbrt.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2jnrqobdi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2lzgzmxju.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gt2jqzriwaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gt2qylujjzw.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2jrobhcov.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhdmkzgf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gt2ahmrkqds.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2tpweqsld.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gt2wjafiuet.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klzznxxc.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2ysyuunge.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2dvwtzbxh.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gt2vvbyhmbn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2fcimnoqv.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gt2tydwgsav.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2kllpuijy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdecdrcu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzsnrrwj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gt2jgnkyhac.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2anrqeygw.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gt2vxubexis.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2wtihglqu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2frxyiwtr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gt2ngzxxziq.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2feorkwwp.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gt2bauvxnlt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2emjuowmp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytuybian.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2utuakvfu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2musxquqm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udjzqhea.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wksonizz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2htaczctg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gt2vgvfeyml.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dayhuhms.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2ohmsogpi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqnxaafh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2taqqhzgt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2dxpyaoqf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2ywnqijyg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gt2wvsoayuk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhnmdxoz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gt2stbwuwbn.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gt2liavbpln.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gt2fgzwunbq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gt2ftfrwhsp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gt2ahjfpnob.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gt2ozlbsbtv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkppzkgz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzoutah.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ufphyphi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2esvifmwj.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ibgwdlxq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2eqoqzmfj.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2zrtabryh.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnjqqkvn.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2acbqechr.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2yjrgnvcc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2sccqljes.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2hynxqoiw.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2cfpmpfxw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lchonrww.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2xzshaxrd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2naxrvvjb.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2gxblqzjz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gt2qsgdnnfd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gt2pbzmxjhe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxjzobss.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2qugadbys.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gt2fdzgehjw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbnizas.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gt2orecwnfx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aimfcpry.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2rkvppbrp.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tivarewx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kaaritsp.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2htebmojc.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2ewtlegcd.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2twwzpzzh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gt2veqfotms.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gt2mdmqavig.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2blmtzzcf.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2yspvvyhx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gt2tkrxumpv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2sqjvvccg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgcwtnnh.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2xninjtob.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdwttdzf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gt2cdouiudu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gt2lhwxfpvk.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgneybpe.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gt2grohwxew.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2dxpxcyob.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gt2oybjdvnn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gt2pztlchja.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2hmifvlxs.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2ojuvolju.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gt2oqaczxsp.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2lxtjczxi.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2psksvpvv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gt2cfkwspsx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2mpbbhspg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2desvcqnx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2tnizcfva.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gt2shbhthtj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2sazrktag.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gt2nyxiozap.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cehkysxp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2utchnapr.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2efnokooi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2qoznfeop.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gt2sjcfpyxu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2awpblqtt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2hmxizarr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2sivbuolv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2mnriyjbm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2yojbasgx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjloknm.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2dxppjglg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gt2mlgqfbdk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2wwtkjidl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gt2jqqozuuc.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gt2cjxdfyae.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2tjkvjjpw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gt2myablamr.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frbkkclg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gt2majrmfir.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2gjnnuuyu.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gt2prgekkmr.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gt2vpagcrmg.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2scfcazxy.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2jsyrkxjj.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2ltskhhjq.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gt2gaoorbwb.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2dlkcfzhy.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gt2slrotwpf.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrzbifxp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2emzakgqf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2jcmgvwjr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2zsfurovj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gt2fupulodj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2jmomiayy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gt2qklprpqb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2hmaudnsg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2msvjcpox.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gt2vwdfbfof.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2bapjwkkd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gt2vqzaejeo.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2aausfbki.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncayloxp.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2zimqrlgk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2lzyreghp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2ofpfmszj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2aglkdvkz.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpodvoml.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2yieiykai.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2grusjbyt.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2hbujbmdi.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2vmzqanuz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gt2wlbiwpnt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2sijgbzvd.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gt2wkzgpdit.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2uuajfbpm.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2pkiyjzzx.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2pavnhbqg.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gt2jmstwnbz.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2exqgzogf.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2qdvbuear.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gt2mbvdprcd.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2fodvjakn.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2djjtixog.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czoilcqa.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gt2ctmwqzux.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gt2utlfnrcq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gt2ipudurwb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2xvkfpjtd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2rnxztwgk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2thasgnnr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2edozieak.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gt2pitskyyx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2jolukvqs.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gt2atnpeyww.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gt2cvmpnzln.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gt2nkokpprq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gt2mggemyhc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gt2jemgzyaa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2zfguxhvi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gt2yqdthakw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gt2vaijjfib.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gt2hzpjocru.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnewotzl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gt2cgjnrdbw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gt2oszmgvnh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ajwofsga.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2ohelxcdz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gt2slnicjvv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2lhsxgyfd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gt2pmuxavki.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gt2fqhgynmd.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nencemwf.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2cimtfxiy.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2biwaaylx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2dupvoxox.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2ednbgbax.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2gfsqwhhb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbufdwg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gt2uoopsenk.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqflzmqr.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gt2ilasbifk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gt2dxbcnesk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2isntwiqp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2ztqtysov.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2fuhsmfzl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gt2aamjlqsj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2pwenivbi.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gt2zcppmtmn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2bjojfldy.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gt2iqrupeor.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gt2eqkktisu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzplgohw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2tpimyolg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2qgnzuxwc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2dfsbynfm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2wfxnmcrr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2otpklbrn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2ttzpnnzw.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gt2vdiwbcfl.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2qzkabirp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2mxeehspr.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omntbwtj.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2yklwqvil.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gt2olucpoln.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2szkmiddn.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gt2erordtlm.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gt2ccdygmvq.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gt2zutotove.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gt2gkhrffly.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gt2iihlncfs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gt2wttqsqxb.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gt2lymtillr.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2qkafqblt.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2tkqduoym.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2mzjqwlpc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2aezaukdo.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gt2ticuaojp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gt2smibjltm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2konxnsxd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2jkfytlhj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2srauycrp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2vrjyijuo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2pdlsttrm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2lueebxsf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2qrjbtocg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mquwqsvq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2onmldkpf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2zlskwfbq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2vcywapwl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2htdisjfc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2blchhigp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvntgjey.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2ouaykilq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2oklftwnf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2onuhacqp.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gt2lluznbfj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2drwemdvi.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2vblucxxh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2jixergaw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2nkttrmdd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2nngaipuf.html


<!-- 参考信息 -->