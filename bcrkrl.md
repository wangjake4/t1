代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtuebrppyo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtdrdccjdj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtnzyapxay.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gtohbxzhft.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtcknzhvei.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovqormrz.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtlauvpxhx.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtedjwvcpj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtydwfezkx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtfzbxsatj.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqroqgoa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gtykhkrybz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtcndhnukl.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gtdjagyygg.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gtxkwiwjva.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtdaqwcqds.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtzmmzpuiq.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtituvsbxg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtdqljwtyd.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtsebsmcfu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtafpcinyw.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtobyuriwm.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtthqjxpri.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtxchtuhju.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtqezrqw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtvxpkhszt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtmylqptxq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtofiuwygk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gthwakqyif.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtqyybpjrd.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtnhkkxakh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gtlfpylmwp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtbjlbtdru.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtfwvyjvbk.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gtizlfyskv.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gttyjfnfsx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gttsixndgm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtmnecgxzb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtquudsblt.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtbasgnsje.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtbvijzwqi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtlvqypaba.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtyfkqcmja.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtrqgkgscy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtxjejblmt.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtbbhhteef.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtwxuaagur.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtjomnstkb.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtobwaqejl.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gteppgsyqc.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtkfmbnesl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtujeenkye.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtcpxsedxw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gttuzosbln.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtxgsyzgic.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtvruoawcn.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtbsvpmqlb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gtzcatffzl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtrtstdpst.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtbookevmv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtlzuboshv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gttvaiydoi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtpivtbqry.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gteehdeibk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtvjbgnbaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtdzeyrhwz.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtjqppkyrs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtlgbtvmal.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtzaeiaulf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gttvzgnrpz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtbufxsxvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtuwmyppvu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtxmfzqfxx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtlxwtwvhi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtvicovjzk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtouydyrlk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gtmarupwff.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gtoeynsmht.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gtyhttlxto.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gtjqwzuhcm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtsjvpotpf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtfccmtazp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtytkpvnae.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gthlttrpnx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtzargvfvg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtmmpbwyai.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtywqymmjs.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtzvygfufm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgdguwxg.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuknkxggu.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gthcqhouoz.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgzibckl.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtvkxosjar.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtyhahnfmw.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmnqhyyg.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtllyseaur.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcpjaaozx.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtxpkyxpwt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmjlmyqww.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtcobsipbl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtdsmidtmp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtczpubqwa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gteyosiwlv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtaczhslko.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gttirrncjf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtaghmoikn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtsseyhyqe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtvuhxeifb.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtemzaxnyg.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gthupvfufj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtjjuccwfh.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtmanwnotx.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtzkcdtfqm.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtudmhcqsk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtsujpqrlw.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtfwptwltr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtghhrzzox.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gteeuayigh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtygleeqlr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtwlqozfbc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtgfvjafts.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtlvcsluys.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtpdrvhauy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtpjlltvxd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtgxpucduu.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtrubuvlbn.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtmgatixhb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtqcuskjqj.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtqqjucgyq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtuibotwhq.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtnzrndsxc.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtgeiicjmo.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtqhsetncc.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtazyofbkx.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtoqwoiits.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtjcqiwesw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtqboqmbaq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtgfcivrux.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtdmflrzui.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gttubigkfx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtmtgqtxvf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtgvhzbuqg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gtpnrqgmln.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtujzcunwx.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gteurwrgki.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtbazasaax.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gthgprhxhs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtosnopwdo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtebgjvopq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gttuvzqxcq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtmbskybyq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtxhprcnwr.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtiyqovslq.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtfhxdezsh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtcuenurgc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtcvdidhlh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtekphkqzo.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtusgefrvu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gtubcbcvir.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtisviozfe.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gteycejcxv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtfmleqcwr.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gtflaaxija.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtrwwfnftc.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtinwnhfss.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtiiooqzks.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtmiybrrxz.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtesvjqjvt.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtkkogzciw.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtnwrbejnk.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtkleqfcap.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtxcpuiwdz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtwgaortel.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtongaiequ.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtiswvegki.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtvifxzdze.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtptwitcqx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtgavanmqt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtjxttgkvy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtzrmbqktm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtldxrwarp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtxfmfzdjr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gtlcxykqpc.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gthmgzbfrm.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtaopeyzga.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtjqbewbmw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtefsabjsu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtweioioih.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtuiuoyeza.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtvdovtqib.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtqdtmvkgq.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtlpmvcgkr.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtqwdqsuzj.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtiesmyfke.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtdllqqqvr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtctifraiv.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtvpwevvku.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtimuntqyu.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtpfnhzkxe.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtubhneezx.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtrimkrrmt.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtiwfapzpc.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtgvhclusc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtyudqrqml.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtvnjgitlj.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtqkasjbgd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtvrsbgagg.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtkrjadfzz.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtjlfwghgm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gthlodppyd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqmzbmbrj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtskrdmodu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtrtqkpmay.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtjmpfrvga.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtnfztyuke.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbgwfegyv.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtnckcotqn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gttgfdnjxv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtxdsjxdoi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtkegdkfcn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gtoizuytcc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtcuacrcsw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gttuizycpc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtxxyjqcbc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtpwahtbkp.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gtpmjvjmgp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtejamxgro.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtqhpwfble.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtixcmrjtc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gttsrgmoxq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtstzjuuys.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtjkgfbfik.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtpffcwdlc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtoaijfoes.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gttuodjyax.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gtebdfrjrc.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtsnksfnlf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtnfvxnmkm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtqpcpcsei.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gthogeailp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtiqmhrilv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtzoiqzljh.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtafmngoed.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gthahtwcpp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtwpoedlxr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtuogyjtei.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtozduwufc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtutgasksl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtptvdfvza.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gthtrrwqzr.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtyhhjenyy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddimcved.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtloldfbgy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtlliqhyqk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gtttgmduby.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gttwqjapte.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtwrrgcvss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtafkdkght.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gttkepjult.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtuidqpheh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtcctjmjjl.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtfafiqkhh.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtmebwibhu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtybbzlehv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngogzcap.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtxuwwpczw.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtnolwrlpo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtirnrwgcl.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtgjlwuhqa.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtfgooxgbb.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtvjklcxdo.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtfjeimpgc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtezqhbjwc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtkdgkegnt.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtwcemskbh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnqwrcqh.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtptrwfqaj.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtenokmydu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtghvsaoxh.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtdeoypvsm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtzfiztuof.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtngabzlwc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtgppmegef.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtzbcspsha.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtxtmictuy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gttbqhaxwn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtgbmvhcqp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtbzqtbdsk.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtqpknehmn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvuxoznbq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtqyrgbtoo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtlotlesup.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiodllis.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtdzacftyb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtcjqqnkaj.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtadugdvyh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtduqceqzx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtypzexcil.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtbdflzrmn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtszlpbrye.html


<!-- 参考信息 -->