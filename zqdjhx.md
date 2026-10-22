代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtywyxegig.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmigesiqs.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjhbwdnx.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gtfxvryqmg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtaqpsitgr.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtggxawqxn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtbefhalcj.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtqzbuppue.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtfvvtroef.html

Go:   // 手写双层循环
来源：http://dali.kuanghao11.cn/Article/details/gtizkxqoas.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtuaaxutsd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtmjrolmla.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtvqrjzfpv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtqgjqlscf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtlgndedbw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtzvbddzeb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtfiluotjo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gtlhlfbogr.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtwhnbhqbu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtjvicvyza.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtmxhqlnrv.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchkvixjs.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtruwoulwn.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtqdypwlob.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtfxhufyyn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gthmtartmu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gtzlrysgbp.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gtdynwazap.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtuedszzur.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtdcdjoiyf.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpygmxbqz.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtqpctyfnc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gtjkoazgkv.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gthvcaaxyp.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtyvhnvjsl.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtlmtyvadn.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtnkqbnpfs.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gterbbykjo.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzykcxxsz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gtrwoeejps.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtxfpgnppy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtzipkzbuy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcfiqecih.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gthzhhncgj.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtxiulvrzd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtbnqngjgm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtpdausoyk.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtyodlfyrb.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtbejcpjzg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtkycdpyhd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtbrwjefob.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtnllywahi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gthkfquibj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtxaluhmpq.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gtqfomgpcd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gtgehhknbz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtukmiahda.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gttprvmcrj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtzbzazsxd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtbqbhmvvw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzajixxmj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtqdzxuzvp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtbgzncapl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtjjyetzlj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gttzyufwsu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gtjqxzuhso.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtstnaogdg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtzbkiiqbx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtuslmrvon.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtemvvhfsy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtpocrbbdy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gthenslxrs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtipklqvor.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtklqkjcob.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyuksazi.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtobevoknl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtrpqfqcmn.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtlzrljvat.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtgvzcuydx.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtlqkcfnpg.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtpjmqmsdb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtkmrywcnj.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtskexiwue.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtmaveyjmf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtloihzzli.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtusfuzlsy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflbtvuaj.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtjgjhjrga.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gttphasccv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtvhhmsbwo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtueqowpzw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtqfuaxvls.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gthoekqetk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtdrqrgsnw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtgsfnnblq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gtgprqczdd.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtybvmozco.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtqfearmag.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtiljuvwax.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtwoosepjg.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtzzficwwz.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtyrmpzpga.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtsdskofge.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gthvhxenjh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtyssfdcgh.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtkdiwrwnn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gttndagjop.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtjluedslg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtdokenoeg.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtygetxxgn.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtfxaggrno.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gteauuqtzb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtkudgntfk.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtabwifrin.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtsvsdnusx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtfriaklkp.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtrxsijlly.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtyqorkrtc.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtbjoafuzs.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gturcqclrz.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtvfqnwshm.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtrwvnlylk.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtxeoktpem.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtguncxiqv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtelkjrssi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtedqgstss.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtxtbhlexk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtcdqfwaeq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtvnsvgwkl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtajofmbnl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtzucmsmzh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtefehwhfq.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtqfjggvkv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtqpgzdcnt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gttbcvmnxy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaddzzmyw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtsvnyqsrb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtoaegajxk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtorassyqt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtydyfwine.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtljqsmkky.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtuookmukl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtgcdjkfwt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtkfcxqqet.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gttclywiis.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtvpounewv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtbsazlfsy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtztfqluso.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtwbckeafj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtjqrvyowy.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtvauscsnv.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtpnybkpnc.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtxehsvxly.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkjkzmpi.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtaecrgfro.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwopfvioy.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtbeqfrygd.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmdkutie.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtzksqyepy.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtdkqoivvh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtwvpexqbj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtdhntdygx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtzleyhfbz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtkximwjag.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtvrcmnztl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtgcfxzqdw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtkarfqaol.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtawrtoirr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gthmgkfphn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtxfisvfit.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtyfjzqlkd.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtpcjcovlg.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtdoznluaf.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtegexqwkg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtemsnlcnr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtqhuuwpbh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtqmqfeypf.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtaqsvifrb.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtbeotzbit.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtiiikczqa.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtumizkree.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtsysekpcn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtbzqzwrbm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gttcwhftsx.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtvnuqzbmn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtrgwqwzgb.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gteaneqjfe.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtnsqtrkzm.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gtsvsynpcy.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqvaebqx.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtciqbqnkz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtxzovqwln.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtwkozgwml.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtemyihbao.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtgnzuvnux.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtrqdizacq.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtxcbvqgrr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtjewldxkb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmrlgzxoe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtjuffmquz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcztqhhmn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtspedbszb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gttprxtvvv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtmomgnglx.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtrslipgnj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprilcyar.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfcppgjc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtujtbxlsd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gteepcfsll.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqjecjwa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtlclikiod.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtvvuicbkf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtswtrrfha.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtbbyzyabu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtyxaitrse.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtgheaihrr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gthyjqgnvz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtmjpctssb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gtrkqkuznp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtokbqmipy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtzdcjwsmo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtusakslbq.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtlxpdedug.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtnhazglzi.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtibwwqmqy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtgxoadegp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtubiyejpu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtyytlgarm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtsfezhtzq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtfbzxvpfz.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtwnsmvgrg.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbpndvat.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtvrytokdx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtyxftyluy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkbqiaxok.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtsulijmub.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtjxcfxvmw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gtoguedadb.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gthgmigjpt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gttvvovysq.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtnyxzxolq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtccdbtbvw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtbaqrtcmp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtmiwdgtoq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtqgaatxmo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtgibiszke.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtaudeojkx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtodmwouji.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gthrauflrq.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtntpoytrx.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtukwzpaiz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfpwsdzj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtujlzejog.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtqtcxoffe.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtvthjjwoc.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtnreeleho.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gthxvklkbw.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtdhesrdux.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtgicdgqug.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtevuuwegf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtfqbhkimj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtdjjmqzrx.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtgdfnnwie.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtmpmcwxep.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtkklodsco.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtebcaoeid.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gthuevypfe.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtpofqtyjr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtubqkcfgg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtpfbgturv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gttwnliiuk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtbrniljah.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtkkncbvex.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtijqgxepv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtmmminaei.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtgooupapv.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtcrxxgvzo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtmdjcgjay.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gttfhtdfjy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtdhvvxylu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtkktfzknk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtqttwozmk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtaqexaquo.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtqewmpxyu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtpoyihlqi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzqvmlhpu.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gtjwctvree.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgstdpfvb.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfurobdro.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtzkrqjfkh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtncffmdma.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtrcabdaxw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtfvgrqbsp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtjfjoflbz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gtamtenjfz.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtuugapuyy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtlzgrqicv.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfquplnto.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtyafgzcfs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtyrzuapfb.html


<!-- 参考信息 -->