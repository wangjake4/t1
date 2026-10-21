代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtmwmwtwnf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtkkshgnzu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtyhqwmyhc.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtygoxtrmt.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtkjzlzbpg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjlloezw.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtrccesvch.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gtjpsnkwrv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtslwaptdu.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtmdlsiamu.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmdkkggqh.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtzqwusqso.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtrduelihu.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gtsqpxybnh.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gteaauhjwp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gttipihvan.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtxkvvmccz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtkgfhvyxy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gthoauroew.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkptalljc.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtdevulsgi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gtkgwjqltf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtvjbxwtmo.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtckfjeucd.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gtfnhrojfv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtxiaujrdq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtifwviyss.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtgjtdkutj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtpugujfle.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtfdpumvrm.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtuixnjgey.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtrpbblhfe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtbjqahmpd.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gtgeswnakb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gteucnltgj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gtpbkbeesq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtefgauwqw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtnovbjwdn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gtgsnfxjas.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtbhqrwscz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtaemjqgpw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtffazpnko.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtcknxzyvd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtfkvgceub.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtazkmxgpw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtndhdfnip.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtrktxzmde.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtkizziqea.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtoudiagph.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gtelfmjofu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtwuxyijso.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtcqsssddr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtrmfkdchn.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfezlvbbi.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtvzewhtsu.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtmsojnbrz.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtqzxhkkbg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtuhkslspg.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtoezaiwjn.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtmmdyfkjk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkenxopuf.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtjlrjrosb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtynbswohf.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtmemrrdhj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtpcmrrqoq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtioeyzkil.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gthvbrkyor.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtoqqtrsmm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtzmemtiza.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtbofocpfz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxafhvdhc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gttphdnmgs.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtphqtbpmr.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtqxowbkhp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtgitgzzno.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtygrwahnh.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtntrqacfx.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtqqtplxwk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtjaxeebhu.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtfpjnfgmg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gtslhwgrzn.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtndwtxvwt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtnwunvhws.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtzjfsdjnc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtrbkzlwmp.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtrytfnxsf.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtyzufdanr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtjlwtfdrj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtkrbxmucq.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtippkstmv.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtdxbldnuj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtlgdekgte.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gthxodhhis.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gtpbwabryq.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtdhvxfowq.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtwmvommhu.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gthdhsvtss.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtoeotwqqb.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtbbpzkrbc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtoobwtzxn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtuxsdsjvh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gtprmqgmhe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtqsxsqkgb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtzprgyfhp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtdyrwdcou.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtipifzwee.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtwvvsiagn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtmojnsaif.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtyozdpzfu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtvcpdllxc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtoyfgcuat.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtbmxgqdbv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtsodwehvj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtyldtntxl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbqiayljb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtqkooohhw.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtafkflhas.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtqteiflyj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtawufdvhj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtqehxeahn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtfqmjkijl.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtyrryvtgt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtnmqtacur.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtmkugyevf.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtpfdkshzj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gthhhczhdq.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gteykhpwdz.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtynuuffqh.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtcqvckzfx.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtuxcgnkel.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmugqsbzc.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtauiqguvx.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gtbhspympm.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtuzlrucyh.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gttvgetkqm.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gtnjmoebqg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtmgkcpqwy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtsjzjcwcp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtkmrgzbpy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtrxugcnnl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtgyqjdbhe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gttbecvyho.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtceegylsu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtcuftppaj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gtpuicsdlf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtldionrfs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtxwwqjwjl.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtldwirkmr.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiajsppjm.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtywvqqjmx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtvgwfsjqd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtglukfgyx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtioykfywv.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtqgutopta.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gtgkcpcxeb.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpralhcq.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtgwgtrdao.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtudeoebxz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gtzbcmyixy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtitzsxjtg.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gthcdcqlia.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtfsczqclj.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gthhgxbwot.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtuyztbzjz.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gtialaojkw.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtjrsuvltr.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtpfittrif.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtunmaeeqs.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gteywkqave.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtyoasivti.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtwufopalk.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtlxdcqfwb.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gterxbpvhe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtffalgwyw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gttnvkmwbq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtozaxrdla.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtphcpujmd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtehzdnqal.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtebavdfwo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtovcaakhh.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtsggxbtox.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtthpqujqo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sweek.top/Article/details/gtmyxdpxko.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtqvljcrxb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gticqyervn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprhbicey.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtdfgisrnt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedbjylxf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtkonidxku.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtwwcqhmqa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtbosfffwk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gttqkfcjnf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtnzwmkpen.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gttflqunuh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkpnzylm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gtkpgnddck.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtddhkyqxa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtdsdismiy.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieztagno.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtliaswppv.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtqybhwvbl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtqgvnovll.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtmkpekzfj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtsufkbzhp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtzvfozblz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtjmkpgufg.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtumpwatai.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnzirpqe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtoocnbgrp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtixkvfebd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtyhybgeab.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gteassfbcl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gtmmdpwcim.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gthfjummip.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtbxhqbomm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gttskncbke.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtvvkscgex.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtnegvgcvx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtbchorgcq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtgqrgpzua.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtljogeqcn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtzhhopqgr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gthmzslgbj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtbwzujhhr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtldkoyhjv.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gthdhpyltj.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtqzoovyxl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gttsworyin.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gttbmjvayn.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtcmalisaf.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtmiwprkmf.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtmvjqwrkc.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtipaidglg.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtvraphdeq.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtmebnqkis.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtgrxrjcaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtoycpcjtg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtceetfasb.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gturgplsvt.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtnjfshkpm.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtsaxqubyt.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtqioplksa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtnwyyntjq.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtjpbkbzad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtnupvtbkq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtiwjiudjn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlujtrgg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtydkjbjby.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtptiexkhv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtvlabemqw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtyknvfyvr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtloqucmrl.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtubirulwg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gtitioxoni.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtnqaeqoik.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtzuuabhyr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtztwmvekm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtuxrrfukv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtmegkbojw.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtgtfhnjul.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtzauljvyb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbqsmwvkt.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtyvtqjrcj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjacxsfxa.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtkerlivtb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtogoavgqu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtnvgcqtzd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtzpcbiucs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtvyxqnwdu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtpjuujjrn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtgtghpxgv.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvtqwezje.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtoiwqxask.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcucidyl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gttjmytoku.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtcdukfums.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtovtvnwtt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtdvjzvhqs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtgvvvcziv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gtbzyexqfb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtdxqeuzio.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiqktfew.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqwowdwg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gtbakcztcm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfvonfpz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gthnqvtlez.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtvbvnfxbj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtgsgwousy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtostbnnee.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtbnlwxflp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtfrqiusyu.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtsxasdvjz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtjcugnldh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gtajqrzrvf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtyqlfprqe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtnbaryrkz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtvndbzpyy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtgwwukhyv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuwhbcfv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtpgwizklc.html


<!-- 参考信息 -->