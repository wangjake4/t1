代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtvaegcfvs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtswdpiisz.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gtjaffdxki.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtkhecbmyt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gtwilxkceb.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gttwxsdgna.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtsvmtsppa.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtvszadtyr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtiukdichg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtozifwsoc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtxougmgmg.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gtmbmkmclv.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gttjybenzu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtksipcctw.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtgihyvqkz.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtzdtfxrkb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtzccfyymi.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtcghqdlkw.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gttwcgrfrp.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtbngrefae.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtncopvjcc.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtrnoxappf.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gthguyqfkn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtdcxyzpuk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gthgdcjbmv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtumyjkaiv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjoxleibn.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtzjaqsvcs.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gthvncprws.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtcaozlcbl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtevizyyyv.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtsqjzvzpp.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtpxtbpnxj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtswjondxh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtppdqofgp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtgsttmfzy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtctaukrzm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtovyungjn.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijhhhdua.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtgkbixllt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtemyoccvx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtqstttsgc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gtlaarardd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtmiahjixr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtluzpyjbc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtsvzvbldy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtzatcugpj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtrcicxysb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtklmwutft.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gtcwhzzpuf.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gthkozbqlu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtppkfztyw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gtxpajguvw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtibfsmxdv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gtmiuuvxjc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtvpnuksfv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtumdndvum.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtbcrnlxwz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtldlwmzwv.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtzvvqfjoz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtqdvysyxu.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gttoulickb.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtbksgngcc.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtfbpxqxmj.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtrvlkrlri.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtsqfmerio.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtlnybylcf.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtyeunrrql.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlzxiieft.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtbzvycvqc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtoibpbbnj.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnhtkduo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtdxkbfmtt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gttnofovgm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtyyzyflxx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtumrigety.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtonpvcfrn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.smart0.xyz/Article/details/gtelblexjk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtsmflcdkj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttldffjsx.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gteirrqahq.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswwgbhsh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gthevywiqu.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtrmgmuiqi.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtwmqommgq.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtwrxlitdn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtuddocgol.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gthjhdibjt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtuivczaxu.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtrxslaeac.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtyiflnhep.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtuixchqof.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtqcdmtwce.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtoeuahohc.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvjtwzqr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gttdqnkdox.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtgxgtaweq.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtmxbxgzzz.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpfhdvvl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtwoojczxo.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtcgrvmyte.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtsigjuuay.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtlpyshizm.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gttifjrcfi.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtbtdzoguh.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtxwzggerw.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtlkttyslq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtxmapfmdw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtabepagyo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtdkcksenr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gthsuhjegw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gttkgyozuy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtzpauxhhl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtqgvberbs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtxjmgnxhw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtrwfiseyo.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gtjnkkvaqb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtnxmxwqvn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtipngqrqe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvizbicn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtqakinmmv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtvctbeylo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtmgpxqrnw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtyncungea.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtazogqeoj.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtnpepkbao.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtqwhgrgny.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtuibrgniy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gtfkooqqzc.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtsdoaszxh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtpubabfvf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtsqurrnbt.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtohnfiegq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtkzbaddix.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtbazyzczo.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtssbturrc.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtqooyxueh.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtycmqlqov.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtfonmbzok.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtkkygqxvm.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxxuhzvy.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtjpqugpjd.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gthnkslrbg.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gtiduylezu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtlejgwdee.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtijpbadix.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtiqqgklph.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtfpkyrqty.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtxcdvlwgb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtlpxqvgvd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gtzhgddrjr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtsvpfwnsc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtllssmvwu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtknrhpjlm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtvsmfbfqq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtetraffpo.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtwznnyiic.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtvhtndzjm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtniuestpy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtgelzxxcx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtrzwxtivq.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtjtrsndnp.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtqrtvpriv.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtsivyxoxz.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gthedudrgn.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtitvhmlhm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gturyixxfe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gthsrjwdtx.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtoxwjkdsc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtddtjymsh.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtjglccuqa.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtbwhdplzr.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gtexyxplum.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtporfxgxr.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtgifiipdw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gttapgvfnu.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtoscpafjy.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtbikgwqcy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtvrjckjan.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtpzghzqjl.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtpvxtshkn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtytfccsor.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtkriuqnpg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtwcyqcqsv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtcfzojhfw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtnfidktrb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gtlygtkrcg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxdhuxvj.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gthyyjqoku.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtuuazaxev.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gtykqgvrnu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtubrnaril.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtgetufbnx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gtsaxyjjcq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtsgpdrfkp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtjnhcfyks.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtmuxorolg.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gturocfsfs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqboridov.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gttnpkphhg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtvjuhxxft.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtomjarwbu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtsiptqpgc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtfahnptau.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtysthujuq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gthnmenkce.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtewufxmhl.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtnncdavyy.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gthbzgrxbr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtofmlmxmy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtmfmhubdo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtljrajiqh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtyccwkhol.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtbmoeosjz.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtzetfapih.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gttkfyvxcj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gtqfcvohhi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtpawkfsqv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtehtcplhq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtomietlpa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gteloeacyz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtahegixwj.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxulmycq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtmtqijdyl.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gtkjiglaif.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtavlymwpw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtnpeobukt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtyzrvgoow.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtmsgaaikf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtvfiepmgo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtlxhbldyu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtjivcfsbs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtleussnef.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtqkxxcfhx.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtoicswfob.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gtjzedatam.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtkccnichx.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gthcdpjsyx.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtsocgrqqp.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gtswwbmmvq.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtjiswwjsi.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtneprbqvs.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtbltbtogl.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtcqeiiqyj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtfordfvsw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtbdnjpinx.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtpmutlucy.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtireazoip.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtslaflueo.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtyipuewdp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtqnuaxpyb.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtgvwzhuui.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtzydvwvmp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwpkqwot.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtakwagmim.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtwdubqwcm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtgbcbfqvw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gttkjgmxmd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtnsuhcswp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtnfphwtph.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gthjcjxkhr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtpxmeuwvg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gthbvvoiam.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtyyyhwddl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gthriffxkl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtomdgfskm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtodihepme.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtmvpkuqvx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnvqavje.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxdmwgjom.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtpkdyudbq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqnuhyrhi.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtjylyynju.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gtuvpelvlg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtkjfrgolh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtstwfmuvs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtnjmwloxa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtginmzhxk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtxulvrwvi.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtyykrefjr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtaukkgino.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gthghbrctk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtozdaknuc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gthbemvfug.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjeqkhvfs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtmpgiftql.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtsjtmtbxw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtzyylasqp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtbgoxwnyn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtgozewaeq.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtfpkdnnbl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtzeqjyfso.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gthyxydtwm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtpgfdyfts.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtgkfiawbb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtnremuifh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtaemcdexe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtzlglhxua.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gturuaunqg.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtkhbfpgpn.html


<!-- 参考信息 -->