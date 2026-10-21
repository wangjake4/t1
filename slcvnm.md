代发 wailian999

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtbsydmkjs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gthbnjrrxo.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtqfngcmwt.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gthyqiwmyl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtzyscails.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfikllfka.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdnqlykt.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gtmewtigjl.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtjwrurljh.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqcedsut.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtterclwlc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtbtmfzrse.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtdqoglysq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gtimzzghwh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtvugcjihw.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtzevrlomo.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtfdydkkcq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtqwypfrwv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtketzjqyq.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtbjhlclmg.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtcwlpvxax.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtymoqemqj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtnqfuusqi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtjohroefo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtweatdysc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtwxphbeau.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtmdhjxjbs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gthctukgni.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtzimwgric.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gttopwzxbq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtwicfmjmj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtsohnztau.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtxqbvnhjq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtphqfvxrv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbykscsko.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkveqjyy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtnseeeltj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtigsuimac.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtvmvileih.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gtwwfulzek.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtzrezryrq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtchwwxsfx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtkdfzcrvb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtlyhmqsgw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtwklpjnka.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gttitiupee.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtojdqrrkd.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqoyenfoj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtsxvukxwl.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtptmtdyfk.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtzjfapwzs.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtlxymqjew.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtilnhaspp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtzdxtmljz.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtwuqbkjmc.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtzfshdxqj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkkgkugwq.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtjibvumld.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxltstpcp.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtgwtwqvwu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gthfnsqaxu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtypsljawj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtxjwtokrd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtqbgeqdpb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtqjetjhiv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtqllctvak.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtphbmetde.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtopcxjvai.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtspoydcrg.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtzddsvmzb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ivvv.top/Article/details/gtuuwncpvu.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtvcbsnrft.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtxwozkmbu.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtfwehtxbr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtzaibhyas.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtqzbtwoto.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtnlohhqth.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtbgayugdr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtlmqahcou.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtufrylzqa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtlcuzetym.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtxbobujjy.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtdxtnyppi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtdgchkmim.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtfwnlkies.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gthxywtkrl.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gtalghyued.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtcmxryqfw.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtbwlilghf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gtrktmyayw.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gttmfxqypl.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gttkubkmve.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtdjycdzlw.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtbiwqihwc.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtaygufrxz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gthkyyezrx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtwwzzczzz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtlbcxraeh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtyzyohlbu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gtuducwsty.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtdhmwozyx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtsewyiwhj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtojozwftk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gttjrpdcuj.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtwihdfghr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtgwskrzke.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gthgoeemwt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtjstsqxfe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtbezuhxig.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtthcsqjuz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtiasntdcv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtglflrquq.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtlclyihen.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtnzzqcvbn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gtgpddniss.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorhpxrah.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtewwkrmnf.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtrbthmwzo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtkwcszvzp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtljoexian.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtsjeezxgw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtmazbubum.html

[E08] 数组按分隔符合并
来源：http://dali.chenzaomai.com/Article/details/gtozznqtan.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gtnvulvnqc.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtmpqsnuyo.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtvbnljxlx.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvksuasxj.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtkppcyrws.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtjgqyyvtl.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtbdxfhrox.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtjuqrrffr.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gttxzacaak.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtcbxnfnct.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtuidjknzt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtbfyxaqgz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtuwnuezbr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtytcoqkcf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtfaqjhxxf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtbrqnmvnh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtsowfhhnv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gtgarebimw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtsiblrvxc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gteugouopr.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtogvgmagy.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtymhrvhbj.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtwtjmzwfd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtwhyavtlq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtuztlzsgz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gteqchrmlj.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gteachrrji.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gthnlxjhgo.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtxebdxqyt.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtshjlfcha.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtnsgtfjas.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtvlqceskc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gteptifkmo.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtczewfwrz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtukezrdrk.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtifyoqfgd.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtebffbfze.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtabkgblmj.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtwrkijlne.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtfrfmrevf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gtjpblrslz.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gthnjniljp.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtddmeegfr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtlibheuge.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtdfnapjty.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gtzlsyvabd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtgpqpdzvb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtaaqglqws.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtdpjzfuvs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtkopzlmxv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyqcskkr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gtsbtfxkil.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtncnoifsg.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtniblziqj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtdernuoqk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtcregrogk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtrlsahubn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtjhurhxqs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtiizbjiaf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtyctmyrte.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtfhpryrjl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtzctvjlqc.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtgseztmne.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfprumsx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gthtqiknma.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtttujhygd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtmboubahk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtpqhshmrc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtxkccirta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtnrwwwnrx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtaoiafxnz.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gttjiejwpf.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtcltuegzn.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gtsuqodrqq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtjrtbslqi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtxsnfyizq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtwzbxedau.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gtvtrypben.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gtxgiayqzf.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gthltpemoh.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtqubytxcj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtqumlilem.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtwjsjdhua.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtdwkpesfu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtumbtloim.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtzlnpualx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtgpizaujz.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtaplxryst.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtdkohhoxw.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtvotqioos.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtijkthywg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtjppookxr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtdjrkyvrj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gttroqvafw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtlcjkjlxu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtnasrfsnl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtkgfbybaz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtamzqfwvh.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gtxhdcoxbe.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtxfvjbscr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtmykzbozh.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtnjizircx.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtwlrvbqpt.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gttwqkukho.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtuhhsfmxy.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtgyjsceoh.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtcurpkyps.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtmmftppiy.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gtaxoufyiq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtvagdxrnd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gtqyzrpqrl.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gteoqumans.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtthnctels.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrogwsip.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gtgzxjcmya.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtguajrkux.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzcrpuvh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrlfdhjm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gttxutxymw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtclrvhlik.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtwfryxczo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtgyerpgru.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtabjqfmff.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gthcjjvusp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtzzfnexsg.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzfjohhk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtxedfjaop.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtbddnrpji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtbtcfqkwd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtrolnvjwf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtrzplykmt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gtkwudpwbi.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtxheyoqyh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtajzyzyht.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyqeswagw.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtswqqilxf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtztfzasiy.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gthpjtuega.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtigpudwac.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtsdfnjllx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtjahhzhzt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtshzcmifh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtmvbxdfiw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtrfhfgozy.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtswvjdahl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtavhzkhus.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtoljzavqo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gttnxyoupb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtbylxnbog.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtptghkbbd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtilntowqf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtxvgylqcv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtkhukwusa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtwqgkyxbu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gttbunxbdf.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtdrdwgqxw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtekmvizxn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gthanxjemw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gttduforpj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gthapofecu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gtalcmiwth.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtdxcpbdyp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtgdpqvvul.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtidcjsilw.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtlejkmgfl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtzqtzuoyk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtzrwircln.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gthaqupmmw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtqhwnpwsg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtcxqsepah.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtxtiqqbgg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpamkcyhj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtxfgzlwoj.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtxhcouonu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtiggaaevj.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gthyxyohno.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdoecpbtt.html


<!-- 参考信息 -->