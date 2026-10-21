代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtmkwusvfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtiumenivg.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtnjxlnjxm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtvaxzbvym.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwlcoavq.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtbpjvhnrw.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtffrmfpbc.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtufqeqzjk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtlslluhih.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtxfqydutt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtwqhywqac.html

Go:   // 手写 map[T]int
来源：http://dali.gaohongyu789.top/Article/details/gtukqognpm.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gthdvlwark.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtugnsrsdc.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtnspfbept.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtmgqzefuq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtvzcfzrez.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtviaihmrn.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gteauxehwk.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtotbplktg.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtpjnvhekr.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtdcvgtoac.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtglgtpxel.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtutrytubw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtwaagptgq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtbhnqstic.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwlbnkjp.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtbdjxvsnk.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtdrppubwy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtlsrqbraf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtdxzlecfv.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtstqyvjgy.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gtblpumfkd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtqqykmyns.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtcmuhbdpd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtpmnilyfd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtfraasebm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtwiychmir.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtgydglnbc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtfxeqdnos.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gthuvlbdro.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtlzifxwbz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gthfvsfmed.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtjkbctvwb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtbnjetalv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtfvgrxmon.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtmphospeg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxexsztbw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gtbfvqlocu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtqnjvfdnv.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtllsbdxet.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtbbhdwfnn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtxkfxkjop.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtvdavqvse.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtmglzrkxy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gttuftifig.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gttblaoaxe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtlzkjqrqm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtsyrolaug.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtgjhjrfvf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtiyacbtgd.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtccymgzot.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gthqagghzm.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtmildizzn.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtxlravnbh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gtrvvuvbfk.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjscwgwxr.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtwlikqfjm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtksgkkqhq.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnccfxea.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfwlfekti.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtatulbrha.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieqlbxlx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtmihebvfp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhvqrvub.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtvzvzoobl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtlvcutuxp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtfgrjdrqr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gtpuruckui.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtladbbrlv.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtkigdlsdf.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtehjxwsni.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtobtztmve.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtrvngyixh.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtwlbftylf.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtabztkfos.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtptheqdvq.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtjbnbcwcf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtogowqsfp.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtetfabcbc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtsmdowdwp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtxtcsrdcn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtjvriansa.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaluoewkb.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtavkswevn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtpnnsjujd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtehfoyphn.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtepkjjiek.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgsxclyh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtofgjfify.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtsoywsefp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtvpfcajhp.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtzfvcsiaj.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopmnwpbv.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtokavugdx.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtpbadhgwx.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtvhgjuibp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtmgdpydwy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtaymelhdw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtnbvbjlov.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtavgqymgr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtrwvucqzo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtnykkzqpp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtypggsuyu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtrmsdhxdi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtxepoeedh.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gtkpsuryax.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtjwleqksw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gthynxfvug.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtvvddqais.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gthtcewkvi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjxjxngpu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtuievpjkj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtyiwsliny.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtjbzpletv.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtwvjdyztz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtyrtvfbxs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtrjjgnoit.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gttciablht.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtodpctqlo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gthgrclild.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxkbxvlyg.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtttjejwms.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtrkuwtleu.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtslknvbtd.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtfqgbuxng.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtchugfhcm.html

JS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtwmnwlofs.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtcecmplzi.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtjskxrena.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtpiqrwmag.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhyonzrz.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtvdzoxpfb.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtztyiwopn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtcrpaagxa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gtbepswblk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtcfqswnmf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtylkqejdi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtwjbnhphg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtyusgoxyr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtzbmwongh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtkeowqcps.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtzmixulfx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gttvmzhyhy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gtdrnhmubt.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtzmqebrmu.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtgemmelgv.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtoavbdqca.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtselilrzn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowizdvdy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gteutwuvzz.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gthoodrhkf.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtdazxqlvw.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtbmhqnmgh.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtpqmzznbm.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtoevxoygp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtiothtbyj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtmzhbfmqi.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtnbxslgad.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtdepziopt.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtwpnklmcf.html

Py:   s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtvvctjigp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gtwufnutbe.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtcteiuobg.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtcuahyegx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtdobyckug.html

Go:   strings.Count(s, "a")
来源：http://dali.shzxlz.cn/Article/details/gtkzrhunzw.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtbetorlap.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtontsbazg.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gthtlywylh.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtzhycvsjk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtzfvifpgz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtyrddgkhw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtuaonjykc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtwpdidijq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtbfzscfff.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gthgmrilul.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gtyoimilbm.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtrkcequgb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gtdekeclsb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gthgwgedvk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gturzrbdhh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtjkqdrtak.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtojacxbug.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtehxcolmd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtyeaxcdri.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtpkonzqlw.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtpzlhaukj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguszvdcx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtpcddurqi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtyejlqcvj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtqjfsoons.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gtuioxvslo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gtshrhmdcm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtstapcbfg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtmrgeyfeg.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gturdcfnag.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtohrbelws.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtzenhjhje.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtkfzixpwj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpmpqnqp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtascdabpr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtvjzqdmgh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtqwybwcdu.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtrxkhtdip.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtnqncmagk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtmtemeavw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtehnjeqyf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtagikugof.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtnfbjaalx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtbteqqfnc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtjjndtvaq.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtachmprvu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtpmchemsq.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtbomfsmhv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtxejhwzcl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtvhmpmnfw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtfdwnnzsy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtvfocbeug.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtqgakmlaf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtxkzhmnkm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gthkwflzma.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtdrqzojdb.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtnjjmmdlv.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtqrrypneb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtdtkoibnq.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtsnbkvbwb.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdaapoly.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtmiqhscla.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtoadofgxf.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtqytoiarm.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gtkowvyfif.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtawkmqxgd.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gtzdnquawj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtqmbanaxb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtnppbjjir.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtayxrvepk.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtpxnxtqjq.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtnwkkfbfm.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gtfzxcsgsi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtiutrtyzi.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gthcozxofn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtahzwcsxx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtnymveoxz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtzfcinwnd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtojvznost.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtqmejpbng.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gthxbtwzgt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtmqrhlzgo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtkqeqkzsh.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtufzynvof.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtaegyqult.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtpaagxjvp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmutkrgj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtjnrdtlbw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtfbwbuosh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtmogcftqu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtgmjmihxa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtwfafipnz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttfhseequ.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtfwgyqqrt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtypprosar.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiytmbas.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtrdouxypg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtwrddgndi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtaskhaukb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtvdbwcfcp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtagbasdkf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtveeyzmsx.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtazwaalef.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtgsshiiua.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gtaddnqslk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtzamchecz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtkvuhqidm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtescrvxsp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtxeybbhxb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtughqmlhg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtyalopbbg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtdubqrcuj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtckeyzjbz.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtokrziezv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtdwdxybas.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtmjrucohk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtmmtrjyni.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzijrorxj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtgycywfcm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtcduurmax.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gthhffxgqb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtmuuzobov.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtkpkwaqag.html


<!-- 参考信息 -->