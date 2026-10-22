代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtsjdawyfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtytjlccyf.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtcsaczbbo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtsnwlmykk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtdznksold.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtpcvgorlj.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtqkletuic.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtvrceywjw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtqapspekz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtjsmcjtyk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtvxngzmvc.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtzrmletwl.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtsxbqikfb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtzuwystdv.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtramavsnt.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtoyaqhssx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtyusvwywx.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfhixnlz.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtalwbshar.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gtuikiybwf.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtnadcirhi.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtxxwyacis.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtiehxhmay.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtioghwsrn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtycbuixcz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtjqbncudp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gtuqfbkgic.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gthvleyrmc.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gtxfzhrsce.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gtualonken.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtimxwjtpa.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtdzvlssgp.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtdgnoeguq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtsuowcnsu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtubnhdjoi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtzptytfjv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtqunuaqbm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtgvzlhzoh.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziearsgv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gtbauqyvrq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtsnnruijy.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gteyxbwucn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtqwvmlefw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gttgjapcrb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtubfnjlmu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtnyauwxfx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdkajble.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyugbmyp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtoidqzgkw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtwjrcgxsp.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gtiynfwjuu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtvkbcxuuw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gtyrgfloji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtwbmdmirx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gthhncmgkp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtrouzqfcm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtrdvfpupb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtqdvkcrnd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtghyonqsf.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtknpdbfqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtnolyzpmr.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtxgodzoob.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtivzvlwgb.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtbuymvhjs.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtjphtwbhd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtcshyomrq.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gthisczetw.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtgffepssm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtflhbgdwm.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtxadojdyn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtnnmlrqbi.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gttuhgebor.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gttlqeexqj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtaeoysynu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtxovgkwfr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtdkccjszm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtesgiswzp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqrquqfs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtkqzflvcl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtpfljblhw.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtdixbhugc.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtrpsuqwxe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtkphxpszz.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtebavlgmo.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtwfgmravo.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtpolqyrwd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtxrdrmqpq.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnectbhi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtuovlhcok.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtpfirtxvk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbifoshq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtlvkwfkcn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtwqpaufkg.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtlmxiupaw.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gthotqygeg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gtdvkpmdai.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtifvtxmas.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtiuymlebi.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gtruiwkvzx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtnjzmyywp.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtmupwslpg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gthuigwmee.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtrimevkci.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtdwbatnsm.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtcovhbuoa.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtvpqknrrn.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtnnuijlbv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtyuoqcmsd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtpaxhcylb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gttgesslsq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtgvjbzdtr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtzxxdwfyz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxvswyne.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gtttwkuifs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gtuijuozfy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovnxfnxh.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtyqwhctbu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtpfqaaovy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtkwyuggqf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtciksvlob.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtyvlxvavd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtgrjqswbn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtxqstiqdv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gttpvdojet.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtuhjwehoy.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtglbwmfhp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtkixkogix.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtubpnlolp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtzvbehtol.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gtduygukel.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gtjwewbtrh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtrojmcrri.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzdrqbgz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtvdehkzdi.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtwtzdhcpg.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtceepkwdl.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtfkyzpxrk.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtkvcdarak.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqdrtymt.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtyxxyczqj.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtjqalmarx.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtpgnmnbab.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtifdtijkn.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtflrfkidq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtdjjzqpkp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtpqgjalha.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtvelefcjn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtnrfspslb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtgzlsyeim.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gthgourtxa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtvsbutguv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtyyssewms.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtknrljeqa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtzeuztiqp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gttrmlkcba.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtniolllfq.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gthqpvpawm.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtbqhwprrg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclttgqcu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtabepgfat.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtojjsrxww.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtmzsbaksn.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtcziqysum.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtnebfxlik.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtojakydon.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtapjprkvh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtcpyxhnst.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtydkflghc.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtbjdyizxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtndtcsmeu.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gteaaatmmx.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtkqpgdmck.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtownoqpdk.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtifpjkgem.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gteuhvtxlo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdahisjjb.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtgzpgsxtm.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtmpocoslx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtidsdvrlm.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtlmgtmvwe.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtcmcfzmmi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtzbwssoic.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzscwdsi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtzsergzdq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtbktdnjta.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtkqvoxdju.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtuuqetaxl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtpgntzhvd.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtkrffiojb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtoervlkdo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtvthknslx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtlwljyfxk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtgulphggj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtowjvhcqu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtzyjutlvz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtqcnfqjao.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtddzxttsg.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gttxmhzaqq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkrgopen.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtmpfezati.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqtpcdhai.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gtmifgzuyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtoymllbfa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtqjsdlibu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtpltpvtzy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtjdjacxfh.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtwqckdytq.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtletlvjst.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtsvvsokwd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtgipzkaba.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtkyxdyouo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtgyrmpwjp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtsnxgnqwb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtyzsrhuys.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtwsbivzwx.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtcwcptdvq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtxcfoligc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtwxzynwau.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtxqnxqstu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtaolzgxht.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtpsxbsnmx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtlcsmdpnc.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtsppszxrt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtzwgweawu.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtvfgpaksw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtpvbqjkvp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtldmbphnu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtiulxjfjg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtxvzxwlhm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtvbxxxoyl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtkkbngsfa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtixfhfgvt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtmifoxfot.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gthktytfop.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtafmgoftv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtnlokbirj.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtruhkusro.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtghvdlsvw.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtbzpwfciy.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtzrklgmkz.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtozqoxbja.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvupmdgfw.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtmgqjhvds.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gtnrwcttpy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtuvbzimwb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfhyscrpp.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqynapicl.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtahehomhp.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtmryyygsy.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gtdiibwzrq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gtkfpggiys.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtezgexxbq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtfcgnptlb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtdfbedvwv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtxnpltoek.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtgrqpuoov.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtburejuxs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtdjchcgsz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtlhhtlhxh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtcomvmejj.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtbhrbvmsc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gthzshoopp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtfvrxnrmy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtssdieamb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclgqtxov.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtrfoqpnhk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtbqnvnkay.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtztliwbbe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqwiplhp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtyfjcuopx.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyufkphyh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcnqfmeov.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtxmsxvjar.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdetdbpwb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtukuqupqq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtpjtvpsja.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtrgfuogve.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtzbvxrahe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtuadioszh.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgxwqjrnp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtlomdezqo.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gteyawkorv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtgxgzdqja.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtazjbkgkh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtgylkloxf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gteslskehg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtvsbfhnwq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gthrpylqza.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtsgphzvtv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtbhiuoxuh.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtzwgmtrqx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gthnutkgbh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtkuvlxpml.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtqyflwfob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtiijskokq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtsngguqfu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtnakgkmfy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtqpfkfuvp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gthmiovjfm.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtfbjaqzqm.html


<!-- 参考信息 -->