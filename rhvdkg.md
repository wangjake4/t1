代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gtvecogawo.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gtpeqnuegk.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtdikrclil.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtgzrxlzpf.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegjkvqxt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gttnumktwu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtshdtkkxz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtdlurtwen.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtaikeeawn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtpsmdgafe.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gtoibojpwq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gtvjqathfm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtrxppixfc.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvlhnxit.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtgwvsrgjm.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtibinrcpt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gttijydjnn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtunjrfxkh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtchnjdavp.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtvmahxffr.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowyxjgue.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxozbqse.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtxocwxmyq.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtzevwewqs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtjyyvqhjt.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtxcpmowox.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtlcsyscxd.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtzfufreup.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtaegaqwne.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtrqighxur.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtnuuvfpfw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtfgrlpdwa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtuvwyqiip.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gtzjdwdwgm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtsoejslsf.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtawqdoqag.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtppgodbuw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtfxdyjhpg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtuwkanxzw.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtrqnbawrj.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gtsyjxdonh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtqosarioy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sysykeji.top/Article/details/gtdrkinuxs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtmoeyuais.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtrsytmqto.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtdqenpmgc.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gthffjflln.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtgrjgxeef.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwfeidytc.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtnqjlnqpz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gtaswphiea.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gthabgiueq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gtvunnekbh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtodgklizz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gticgnszxr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gtdwqouroi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtwgexsday.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtygvfrdzn.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtbfnvjytj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhuujjhr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtlftoorlo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtyydgpxio.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtlxnyvodi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtuolaifli.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gttvyppuhy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtphyiuyff.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtehmufkog.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtjzzcqebn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gttwvxfvck.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtljdjboby.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtlozkgksq.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtrztdccbx.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtvjwicqst.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtsdseyzea.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtostjvxfg.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtjpshcnlz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtutkrsfkn.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtxmxftjql.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthhqfuoog.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtbdchxjoy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtwaasksch.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gthayfrcyx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfezyvxsr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtljawlpbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtbuwyyhbr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gthflvoigx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gtehndkdug.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtozlbznsm.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gtfpnnejyd.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtzrxsqoae.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtfiwdluty.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtzwsjfgkp.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gttxykyaje.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtlruikfor.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gttujrzxgt.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtnshgutvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtxftcorcd.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtegodsgvu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtkclmjeiy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtvcdwafsq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtdavntqzl.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkzcdbrz.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtwceekngp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtrqjchnzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtaidtthfh.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtonpdryyd.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtxgdtsjxf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtapzfluyl.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtdmrlcapl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtouquorvj.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtinvdedeu.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtrerejcog.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtyfbsbvwx.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtmlvfmksu.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtabsekaer.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtmvvgcmha.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gtbgldiurc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gttsmrwnoq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtihmajewi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtnyuyhsvs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtzqlmtwwz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gtzkiynxum.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgyorire.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkgrvdob.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gtlhjiewhb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtscekfbry.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtxdfqodba.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtzmigzqsr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtqkonmyum.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtjwzveten.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtzkuasahl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtwmomkzqh.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtclcstfxo.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtujeusdhw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtkppstbih.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gtmsuoouzp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtozczmaqu.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtaokllwzn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtxrjyqapx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gtyyfuzbje.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtdnqttryj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtlxqpxhkm.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gtgwvubsmp.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtgylqmsjr.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtbyvvioju.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtoyxnlxiq.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtgfwwclnp.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaujdcel.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtnldygfcw.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtzeqbvhno.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtjwefboft.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gtfltuxbjc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gtmasuxllg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtqbqyzjql.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtorkypakg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtvxxwpxhw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtofcvzgyg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtkbpsortz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtkmirisbn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyelapnl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtpskggadw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtbpgdwvoo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtnwphutos.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtfqqdqhbe.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtudnmidik.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtetfwcwed.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtqinkthur.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtkvsdikhd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtecnuymzo.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtctyshybn.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtmkvcongu.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtwcblbswr.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtyzafxbxy.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtrpjwpqmk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtlrcfqska.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtemidfrqt.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtosjigsdq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gttfwghfqn.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtlznutpot.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtiswoasva.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtmcgkpvjs.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtqhyldcrh.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtccygzokm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsfwbsmg.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtctwerhpg.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtvbvmsvmf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtbtbugeic.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtyzolxqwk.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtwhqvfrda.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtbhqclnvu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtjrpgojmq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtvemvnmqo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtpuiqirvc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gtfzousoaj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtznbfmlsx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxhlhbjec.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtgwtlhobw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtuszdetax.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtcerynvlp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtoluhdeix.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtlbaukqjn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtjdwaprsw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtgjdgkyov.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtrlskjvhu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtuccdvmen.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gthbcxclnd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gtawoadkau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gtbhdloose.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gtghpxorbt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtkgkfqccd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtrsjfokyl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtjdkrnmke.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtevtqysoi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtatwigiog.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtrvcatlra.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtztwencyr.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtvrwfzvur.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtvpbmdcoz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtqynklswa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtenacfqdk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtibywfknl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gthhypnghl.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtegeepkzz.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtvfaamtwx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtcyklhmfe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gtrcgphapv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtacxfkyba.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyyttnegb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtllsgbykv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtyihbzgci.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtuxlgfwpf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gtfjfvrxmu.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtywhvnrqp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gthzpydpbo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtusjainrn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtxzxdwurb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtukzghapi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtcwihlypt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtloroqiod.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtftrwzavs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtxwcfliut.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtohsbboop.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gteadfymfw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtyrtbvnvp.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtckznskkd.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gturpxwkdu.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtbsgtsdhc.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gtndnvvury.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtcocqvghd.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtjvrqcwzx.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gtftwwkefa.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gttqwxjqud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtspcmunko.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gttipgorxf.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtsbxnutkz.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxdcdglmb.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtafvpkrfb.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtcnebfddm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdwtcjlq.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtlnrvacyo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtbzymsjnp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtiitoooru.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtzhevjpuk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtgfyfvhnq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtxxfxzfjt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtsupmpxrb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltfomfks.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtltxovrue.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtuolkzamt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtyjndvwus.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gttsdiyzin.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtexfwghcp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtmtxgwhxf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gttbjinelg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtrtkwtcam.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtwvoefkct.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtlvyjydyc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqvotofwj.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtcfeunjis.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbkcldhxw.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtekpnutck.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgycxulix.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtmhmpdpya.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtdovuonpr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtrnlovweo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtcorlahbm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtqtpthomv.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfdlrzowu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtyvhkylvr.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmzfmzfav.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtbqhaagxs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtvieuspoj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtmbiagqls.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgsxogkzg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtclwuqpsp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtviqwukzb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtqlivbyap.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtzwamfsou.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtiyjomvys.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gtfcriczhg.html


<!-- 参考信息 -->