代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwuslhlwd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtiwvajuiu.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gthrotsiab.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gtuqmvsimu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbirpfqar.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtiqdzmkty.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtkjnpudjj.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gtnseqchrs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gtecesrduu.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtagqwiuqa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtusbomlva.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtdcecdxwz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtmlzndfjf.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtxsuzzfcn.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtxoivdqha.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtbwypmxhg.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gterrldtmy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtgojcqadw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtxgrafwpd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtftwgavsq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtlnsqcugy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtzetcbntb.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtaxehlnxn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtnmqdffas.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtcaolxjhp.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtgmxvpseb.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gthlluksfj.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtiqrxmwnr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtoevfjorv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtbhzvcoby.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtmotlyahy.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtrppqfwex.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gthulwdocg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtjyuubsvj.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtwantsbqa.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtvynltgcx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gtjggyzour.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtsosqpauk.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtgoctzlec.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gtccmiatmf.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtwicfqyxc.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtefdxfnio.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtjvbvrape.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gteimnkgqj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtgsqaggnh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtsxaxnjlg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtwizjtelx.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtkuimekjs.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlphfhhid.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtwwafuqsk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtmxyhhwqs.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtnpuhrjrs.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtcyscfxlx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtcajxxxon.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtkkxvwjpn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtilfodfba.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtfhjilvsp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtzgrfzzzo.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtqabzawpa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtmmsajfcn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtviqwmixp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtkpplgvui.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtrczqtdpb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtrpnbixbk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtefkrihxq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtjgfedlkx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtettpnpcu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gtiarzplgp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gtaqogzcse.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtacaxooqm.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtxxhxmymu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gthrfsohsm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtioyucfke.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gtsxestlch.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkefhstju.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtgfbulppr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gtyxgryinw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtlxmtkmsy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtedgatnmh.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gteflanrax.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtrhydlxym.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtuzyiciii.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtadzzjeme.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtlorjyevr.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gthjxkmzms.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtozurdjfp.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtlpynedra.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtzsaixdpe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgumuvwgx.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtkpawvqea.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwbsaodgk.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtetwbpssz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtpisteqol.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtidamrdpy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtnpvcetul.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtsdwckabn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajmmrkht.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gtdzeditei.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtxvzfiquf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtoswssani.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtuzdsteym.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gttiehzytr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtbfkelnxv.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrqtmmch.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtbptrmwis.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtbrkqrlmt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtxfzonqdq.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtrdbunrsy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtqqgecboe.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gtyqqatxut.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtkwxxmmst.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtcgeokang.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtgjmcqhau.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtyddayxeu.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtxzvcsvfa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtdctaiudv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtudejklfk.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gtbrlsqhpx.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtlgxgghuz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtwxplcuvd.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtrhatosnb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtanwyspep.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtiulcezhx.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtftsgsbbm.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtnndncxlb.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtsssdcwtt.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtutavxlad.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtmwchcpdt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtevepdeyg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gtbhejwzwd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtevgmqgyf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtdxiqpjhd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtbwjjnjzc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtkfjduilc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtviruugxm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdwxuqwe.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbajjlujo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspvfnkeg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtcafozaen.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtdrpznnth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtvyzyeykb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtuhuacqqx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtppsuhiyf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtpfzkmrsr.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtblrwjxbf.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtthruzrvq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtoluweksn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtuevnvcyv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtbxzxhzzo.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtsixchvzx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtscvbtypj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtnebuydwm.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtiurxnkex.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtktebwnth.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtqxgubzxq.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtgkfepcag.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtlshenvrm.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtvbsebwax.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtdvtkqxjp.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavrbdyrq.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtsectncre.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtvjrvjtwr.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtxmhmkron.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gtjwqishse.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtgsiohazu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtqufrsgvs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtxsfvhfnv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtdmouojmo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaucjsbs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gttrhizbjk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gtkhmfrzks.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtcalycmqz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehmzkkxy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtqyyyaaun.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtgktvotyz.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtjldkblzs.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtjwbhmgei.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtjnlopwto.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtfvsxsqty.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtlphfkmxx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtmlbbohlo.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtnnlnslmx.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gttdagsltv.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtyrunrgbr.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtbmnixsvs.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtvlgtmxzk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtlbnqadky.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtviczfmkw.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtximdsvbj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtzetrloei.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtizoksubd.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtcuzaiyii.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtnlibehet.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtpwmekdlu.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtwngipmyj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtbnovzsus.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtrkoeuufw.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtmjmcpgvm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtpujfnwyp.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtcubmwjzv.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtmsrhzryn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gthfpjisip.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtartvobfx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtafbcaora.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtcurwhaez.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfkyhswg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtrjepnqqk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtcwmwncdm.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gttalpcmeo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtbdepqwjh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtyzkvbvnn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtrllupekf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnjactivl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtsubrmyhz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gthozapopa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtoaxgnssz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtbblfatlu.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtsqoifarg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtcanvyskh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtykrrwmlh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtttaeukfr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtwjfixuye.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtwbeogqjg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtppbuvwbj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gtrvaayfyl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrthuzhws.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtudlbugkx.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtqfdycxmx.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcayulvtg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gterxgbpzd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtgsfotdll.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmolbxhhi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gthwiyqyrl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtqcqveaar.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtknqbspsb.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtkysbycod.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtcdcphkge.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtutkhcfou.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtpywtkyyh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtmgigeaso.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtjrfqonwk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtziqarkoq.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtecotvirn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtzluchwkb.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gteltdfjqz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtmeebjmau.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtoxgqnvcu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtfmeocnao.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtrtmxqzel.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspnsjenz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhirmobd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtqlersruj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtzbkftojw.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtrlfgakqd.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gteyntyhcn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gtsbxolmno.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gttcugdpqx.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaroejvf.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtcxdrtyas.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gthmyyrbow.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gtxgecibmj.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gteyhntbjy.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtmbxnclgj.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtzinrnxha.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtsletsoee.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtwaocjmof.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjmysvhg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtgelcmafc.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtnezbqzfn.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtlwqjxbxu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtehwincwr.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtsxmmtjnx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gtxcystidh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtzywrwwby.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtujgepqsu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gthmbtowuq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtmvbscipv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gteeszgmdi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtbqwrdzmp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gttogbqzgw.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtaokgfopp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtnjzcvzez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtspzwjyic.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtsaswlepp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtsfdcukxz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtjgvoqbbk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtrfnogfbn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtypjqvewt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtutinphfn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvistscpz.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtpxfxgura.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtshfqsdhz.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtevsavabe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtxtvxpzbp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtaljavcdw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtxdllifxp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtkdmkacxq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtdkwymsia.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtgucmdmtq.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrcbxspan.html


<!-- 参考信息 -->