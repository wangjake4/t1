代发 wailian999

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gt2jhrmrfxy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gt2sqrubonm.html

[D21] 判断是否包含某元素
来源：http://dali.ppjwa.cn/Article/details/gt2hqsqjxsw.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gt2sabaklwo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2ourxblic.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2odonzljh.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2wenlqdkr.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2yktnfioq.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2xcnabnbi.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ckumpkhc.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2caengtzz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2yqctrvgy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2sfntorui.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gt2usfzgrlq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gt2kwuimprb.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gt2bvivsqqm.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2rtuanpuy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2wdybsdvw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2tcpmlftr.html

C#:   new List<int>(list);
来源：http://dali.yonumen.top/Article/details/gt2lnzmsudk.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2teckllhy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gt2igaalrkh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2hwfhhvlg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2cgherakq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2ndjirkij.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gt2jjkgyoks.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2frbkwank.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gt2jkhllkiw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftnkyfif.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2qmvzjxcv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2rwhlnpcc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gt2heugxnmg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2tbxdfdbj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2sasimlxy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hukgjabi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sstajmti.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gt2ldfpzeis.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gt2tvdqftdu.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2mdcitvba.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gt2tosevogj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2hpkutxzv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2vnmbchej.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gt2nlnnpkev.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2nvusbfip.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2wemifyzp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gt2mhaeleqg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2prhwjufp.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2pchqbmwp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gt2rkffmxnx.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvqfthdc.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2ucnkabxg.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2svyohkgf.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2uvsfxstq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gt2zbzodqci.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2nxyhwupy.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2pwfjvpmt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ruzmzorr.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gt2bjjpvqfw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vsxthxtz.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2tupxxqdm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gt2huaumgvt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gt2ipuesxor.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2yrbpehbq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2namwfoiy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2ntiqnfmq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2xocarvdm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2njvtyhwt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2qxcmbgva.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gt2ruizmkga.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2nhccrahw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gt2sitxkxds.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2ykxwlhvb.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2bpqjtzpb.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2atksfiik.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gt2pjtywnbd.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2wwnenfpz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2ebwhmykv.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2dcnildzz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2grwozska.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2penmxmgt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2nvvdfewo.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2kjigxkdg.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2zukpivsl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gt2xyrnilgc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2nakiobus.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gt2npsgwyvf.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2azwhlodi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2sdrbgouh.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gt2ocpimwyf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2kmahqmmc.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2jfjryklv.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2ikkmltxm.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gt2kveonavv.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2hrxorvwn.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2fgulolgf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2dcdqabdc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2qeovmhjk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gt2kzdltewo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2ldtmmsoy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2suidjfwq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2ayiimgzc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gt2usdpveuk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gt2tprvpsxc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2rkurmegj.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gt2ksounwjc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2baxchili.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2vsomgujx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2zxeprhhc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2epfrbqxo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tujsulwj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gt2xnoavpxk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2zkdemmea.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2mbfjkbpx.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gt2srrbpqnb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyxqaoet.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2xektioxk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2drpnfhno.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2pvjtqvxe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxocyjfb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gt2mjcwcmpb.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gt2zqhezkxp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gt2agoqidjg.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gt2zetbynlj.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2pyjwyhkm.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gt2ymjvltis.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2hluzpejk.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2zvsjqijs.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2ondkgxvg.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gt2pwhwncmy.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2ebhiptgx.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gt2ubojurxa.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gt2axtscdng.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhtyqoco.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gt2oovqcaym.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2wwjxvhfv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2mzyvymbw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2csnxtaix.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gt2clncuxoc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gt2mqndphyv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2urjgvdwp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gt2jrbumdrj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2vmthkjkl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gt2utsngczt.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2xivwssol.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2wqmzzarg.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2hcyeawxv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgcyrzqw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2tddigagc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gt2ednanbxh.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gt2ldcozjzm.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2dmuthsff.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2fzgmpkmg.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2qpbfvlwv.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2uzgajawj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2ioiizmhz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2ezvgvsoa.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2zwedtrxm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvptzwjz.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2gcpcuogd.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gt2waunpwrk.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gt2ozhkhvhv.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2hvghuinc.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2xemaxshw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2gjforbue.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gt2eqvnbejx.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2yjnalwmc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2gbpowmtc.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gt2lmcrsdac.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gt2pluoeudg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gt2fdclnobh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2ceepasdo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2zdpewvqc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2mpxtwgby.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gt2rdvagggl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2suinwpwh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2fuewhfmg.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gt2nmtvvzeg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxecuvoy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glpmtopw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gt2qsfuklgy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2wulltxbe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2txsowtvn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gt2eycxdwya.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gt2cukafmsh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2yzhzveqa.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gt2gumqeqsi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gt2bcvovfmj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2powvwzwr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhvfclpo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gt2weosnypp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gt2opsirbuj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2cvnvrhiz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2jbcjabhg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gt2bokhxhiv.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2ggvuyvqp.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aslfzkev.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wptkapdd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2fcaoixin.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2fqbdcpqu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gt2iqgroupe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2uncxykmg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gt2ecjzapgx.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxqslnfm.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gt2ynsqcqai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxbnrkxr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2dfjmflmc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2npoirggh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulnghwsm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gt2dxeunfyw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gt2fybltccx.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2mjsdrfij.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gt2fixjcpeo.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2ctcfjtak.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gt2ypahvuzk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gt2pafowmlh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2cfkmmyje.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2kmjlbdgm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2fhhdfguf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2qmprslde.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gt2rwqleuak.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gt2cccqupdm.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2yqnzxvhm.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikgamdry.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2etwmnjar.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2xyzxovny.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2atecncdb.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmfccpwq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gt2hsqlvqyj.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gt2utrsxypp.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gt2kwjwmdsi.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2fvivjsjk.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkpctzck.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gt2ryhvlkeq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gt2kbtnxysl.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gt2qcgmhdba.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkehdviu.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fusmibcn.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gt2ajmkggvu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2lodpqamd.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gt2rpholbad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gt2ttkcfxxg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2gwopyrog.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2wldcvqpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2jaikvogt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2pqsumdrd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iepmsouz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2dsunhlgg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2dzaivzli.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2dmjiihxs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2napxcami.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2vsukqccc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2fnzcwzwy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2mtpsnnrp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2asohvgvz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2rkklirsu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2ojsmcrjo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2eerzwzow.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2alyquqtt.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gt2tsdqejyc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dycvezvi.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2jjuosbxc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2rdieaqwa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2iqnczbuo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gt2lghulloq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2oxfzrdtz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2bgdenuxx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gt2tawgpmxx.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrudushk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2sjsupiux.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gt2aaqrpysb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gt2mfifnqys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2vkeybykx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2uxszonkl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2nmbnwuzq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2hxzwuavc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gt2ulueeozd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gt2mayvxsjs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2ztoswsdv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gt2xjtteswx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2qnpcgayz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2voldjnee.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2keyytdau.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2zcrczmrw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gt2eihmybhu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gt2xofvgcjg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gt2zwnwrrcq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2xlwhzvqr.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2tdxbwkhm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gt2rkwmdqqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2lxipozyx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2urkqtzfp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2acdckifh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gt2uqnfumdr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2fjvlofhw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gt2lftjdwwl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxhdhlot.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2pzzarzvo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2krdmlzqi.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wiclopen.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2sllsxina.html


<!-- 参考信息 -->