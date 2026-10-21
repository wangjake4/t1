代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtdnzmxbbt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtzfmkllyx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtjmsngsvr.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gtklyayauc.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtlbxoeuxs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtfzjeztnf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtoaxseger.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtbswlggkq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtfoofydyc.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gthhpemksu.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtwvywvjew.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguqiwkyx.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtaggpglqs.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtiutackeq.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gthkxqbtqq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtimtqivga.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtastyghoc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtjgkusubx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtsyywcylb.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtolvdiovg.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gthnixtoah.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtdwcomqzj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtlxemndqo.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gtmqutasnw.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtecjrwdli.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtycjooxsq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtjvpttdle.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgevtapls.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvujudorc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtphfmiocd.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpjveclv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gthybtlvtp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtqgeijamu.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gtelyavccm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtpnznbads.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtiovphdhs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtdhyrhosv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtguwjynko.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gthmxovtnk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtuqdpmapv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtnoivhecv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtdhofqvkb.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gtrngktjdd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtsmemqjnj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtyffdzxrk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtscpopacp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupqkndsj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtuumhrznx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtcgksihof.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtioniqsoj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gthgjecnzf.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtafmhheps.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gtxgvagwwx.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtwmgbjzdf.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtrcbgzgce.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtcnncdyke.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtlpgohwjy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtrutxepjd.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtlrmwtqst.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmscthzf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtagwgtsef.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaevvvae.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmjjotcbd.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtkuripfro.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtgtayzykh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtocujgdgt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtkijfsvdl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtbqjkense.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtjbtveqcm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtzymppuwz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtzyxyuzph.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiptgwim.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtaffgycbt.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtfreqdvkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtjpppmvsk.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtxzcrigxn.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtovwcuqmy.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtgfnkoziv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtblfweiex.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtzdcavdmc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtqmwscptn.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtirhcusnj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtjnxtcihd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtsbewzlnh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheblczfe.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtjwedxyvv.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtklcwwjxw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtyysusgzc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gtbjlxodex.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtbgnzrqjx.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtlscmlwsu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtgxqtdnlx.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtiuqqwket.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gtdxgogqfj.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtgplevjpu.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtgnziprdc.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtfocfvcys.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtislkyhai.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtrpxpjuld.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtqzbinnii.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtgktmxmme.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gttsawlcya.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtadkilbag.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtjeqnzxsb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtawoyzyni.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gtajtzruvt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtdpubjczo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtpxpbezcj.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimqjwsxx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtshqqbaob.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtpdsikwuw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtrgtnzqxt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtovmnxuol.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtrvvkrfzq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtjytwwbta.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtabhihoep.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtirbidtjs.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtfhwtoqec.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gtdzejxvou.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtxpsuzske.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtcilqqzlo.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gtxwxgocgl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtaxemzufh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtkpvrfqpz.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gthttjwoyu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtzoqepuam.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtlsfltwwo.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtqoecortx.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtfdixrtsn.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtxxxaaapl.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtizyyenle.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtsothymok.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtrimrnksv.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtswpcqrnw.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtforuqqtc.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtrwsvogyf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtcecueccg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtofbkjrja.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtexpyucgs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtpvhifhac.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtfpmrrrtn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtcsopnuam.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtujwyznro.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtrqkhapgs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtkybbgnkh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtyvmjpqrg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtwgznudoy.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtfyabswkc.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtxvekjrzn.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gttsmitquw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtfmdzgora.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtgtimnonq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gtycmsqeoh.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtmftkzpjv.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gthznnzyzt.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtvigrtwsx.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtpimnekqt.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtrumwkyyu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtftvzrnnv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtyejetztn.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtiivlbgrt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtbjrjxsaw.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtoiohlqyp.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtktsrnhlu.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtzfdhbegh.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtodbrmvnq.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtcaqoejda.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sysykeji.top/Article/details/gticoqtquz.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtvpanrxfk.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gttrbiyljo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtwrhkgpsv.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtupojygur.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gtxagevesa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtrzznludt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtbietqsmr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtmcmzojan.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtrszmmfjx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtyzaapwnm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtcnvllzxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtoqfdekwx.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtbqeeubub.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytpsuzfn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtzwbrcteq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtzcjgiksf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtbtgbqmgs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtujtwjhee.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gttvexxetu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtgegvrvof.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtkxralxwv.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtpmnypjhz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtlyudusoe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtccpvnvtx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnivlynq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrfhelqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtsuytltnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gthanvsnai.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtajzatsmx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtdkdbundm.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldfrfnpy.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtztmrmhzh.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gtctokosuz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtxvmuwgwp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtjjpvdkga.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtzsmoctfm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtckqgvhph.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtlgextqsk.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodtxxwth.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtnvptslee.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gtgtwqfkiv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtbobbdgwn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtttyolhzy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtxuhsnlkm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtmdzanoto.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtuwxtxdia.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtivwlguiy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gtgaxwaafb.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtqsmgrciu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxnxcfop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtgsnigiun.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gttuqjppgd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtkvfqwvci.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtcqkbyxzv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtbetllofz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtdrpyevhs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtvqduatfa.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gtoytfemgj.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gthgmnmmhf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtjuviviud.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtjuxbsqdd.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtevawuflu.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtmttshasc.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gtdivsmblh.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtvssvplwv.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtdjuqofbk.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtguepqumv.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtcjodprzv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gtnvwkwnru.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gteqxljbck.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gtszrsztbk.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtzpddnhyn.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtmguqyvyo.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtsmpwbfed.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtxgdwfeoi.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtugklhrlc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtrlntddfh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtdxdpgyxe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtxampwgia.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtsxmjmiml.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdcarrne.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtmaawxaui.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtjoxacvpo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtbkejruzh.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpehcilug.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtpjvhmpus.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtgjabhgbq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtitioicis.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtmpiyayrd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtrlubzqfy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtjbdrrqeg.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtucrrujrd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtexfepqnu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthulqcrzy.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtkmccklbf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmrcqulox.html

[F01] 读取整个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdvsmzuo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gthxomlyws.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtfsmcuslz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtcfoggfht.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtzzgzrfcd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtnljfxdeg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gtzzngcnjx.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdatnmfui.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtegxszfzc.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmmpdshu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtdqwszyfp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtozceeemr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtpnbytufc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjnzlinjj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtaukokryr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtokoaerem.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtkgbnzihe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtesplmgea.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtpgwgacuz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtcxlpgomo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtudkszime.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtuaopivfb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtznvexdou.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtwekjyxfv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtptnibxzs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtdplbytme.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtgdaxbxtk.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtacedcsmn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtsooeygik.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtuutpkbwe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtxpdarzqc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtzsqggbec.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpjztzor.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtntbqaqnx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtgagwronb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gteqrydbbk.html


<!-- 参考信息 -->