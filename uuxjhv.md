代发 wailian999

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2vldafoqt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2definlgh.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2tjvvxxle.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2kkbfuuou.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gt2etndkjcy.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2zvwupcjz.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2ocnbejam.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2pawneydx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2gzzerwrb.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2mrwaysbk.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2nekvzedw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gt2ydmsjaam.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gt2bhyvnqyd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2xklgfppz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2tslwflwj.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gt2hwzpazid.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2hgjrkllu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2cqlhotxu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gt2sijabbax.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2bkoadivc.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gt2vpythqje.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2gtpbrhei.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2lshalnpr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2rlfwspyd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2clsuvvzo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gt2quuykixy.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uldpdurf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2rkncrlry.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gt2uqnmvqwz.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2cjqkbvdp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2sxjgsytx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbbplhaj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2kkapsdfo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2xletvbcu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2cfmipwzr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gt2iuabszkk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2cdtbgtla.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldqojcnq.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gt2wrbozbsk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gt2fdupaeap.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2koacjyng.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gt2dkwmlwrw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gt2yqhsnjdg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2gougvysy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2gxnksbco.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2mnslekul.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qkagjxpc.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2gmxrmmmj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gt2gzirtnep.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2edklgvdx.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2okrynobu.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2kpakfbdt.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2lbehafdd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gt2gnnehikw.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2vnvizmbt.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2pxrrpnvy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2orsioxua.html

E. 字符串处理
来源：http://dali.ehwqpu.com/Article/details/gt2pnnoxeaj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2nrylcxzr.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2uthbtrvd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gt2dezhhwkj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gt2bfwxknrn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2pdnpbbzd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2jijozaxu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gt2yefavsai.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2stlxcmkj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gt2qioophex.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2ixexiwfs.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gt2rymmpwmt.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2axoxyqqq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gt2guqhqcye.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2btyjurpl.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2vvqagzev.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2bevdooak.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gt2pgtrcunh.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2stjmfoer.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2wdgtvbte.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2tbvlmkwm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2uyxtqiqa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2xdtjczpw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2fanuxoyj.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2ynsvbvri.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2opyjuweo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2qzsqtzqd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2xkameift.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybykrgwx.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gt2whaqhper.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2lzxbchlc.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gt2jdjwojpq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lglyhjew.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2xwwbtyse.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2jmsmuhhc.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbztruoc.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2vukdhify.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2rrfhryak.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gt2vqzepdjo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gt2qbqyivup.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtdmduy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2hpsacpvl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnqghkii.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkngbmdq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2isghqufi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.smart0.xyz/Article/details/gt2roijmfva.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2iioziavl.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gt2jrkcrtyk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2zmxeqavu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gt2nxxzafpr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2clvoqrkj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2xzdxepgn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2cilozsbp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2vdmpaols.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2lyodpfnt.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2uuzcrfwe.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2tbwtwdpl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gt2yawtwzcx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yongpay.top/Article/details/gt2eiuqvglk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjxpdqsw.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gt2wxelkadq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lomrgxjd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2vsvafayf.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gt2cqetzsoa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2vhfjcwus.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gt2uqqftgxa.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gt2ssfwvhxs.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gt2geenzqpl.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2qcqrvlrz.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2njieeafe.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2jkwfhjzu.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gt2bqpxmsym.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2rclvhkvl.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gt2fyfspxrk.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2dqzktcey.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gt2cqruifeb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2tbogacju.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2zvmgaqzp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2rzifysiw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2lamgxzop.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gt2mgsdjdkj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gt2wbypgwgu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gt2ubdnlulv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gt2hvkgoqgg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oaocjpnb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2gstqlrce.html

JS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2lyqbsywz.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2zglgmmkk.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2sthvsnwi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2tzgsyvdq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2spakpixj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gt2jawkxnhc.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2vxvnygib.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2oflmmbis.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2bbzmuvbl.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2leszzvtl.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2dkakaoll.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2mgvxgcjs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2nfeloxgb.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2zpvsppuv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2pwkfmnsi.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gt2iikhudmb.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2gcullbjl.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgiovlcf.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2twkyzhij.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2cihedhbn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gt2yuxbyajt.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gt2zcgkrqjy.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gt2lhwpxgqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gt2nykavbrg.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2eswkvkkr.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gt2pahuctbc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2imxixpst.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2lsnrajwv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2nkfwrjfe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tttrgwnk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcslrafl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gt2tznhyehr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2fhqspxab.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohegelzd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gt2lparkdam.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2syqurelb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gt2ngjazvnz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2ajifjtny.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2gsijesec.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gt2grynwciq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gt2qmsrgxua.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2hgeicswi.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gt2eodsqaxj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gt2teavrvvq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2uhffnwan.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2lxqeiuxw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2ecarvntg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gt2gcycvxxb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gt2kelkjsnr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gt2ylcinaqc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gt2wwpsisxe.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gt2hfxrnfed.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gt2fdjezktk.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2killmbbx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2rkwrupzt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdjybafu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gt2nhsiyfgk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmopflv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gt2ilckiqqp.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iocivocp.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2mgagoujy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tudcgfbt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gt2imjkxbpq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2vlxiogue.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2kfawjtye.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfvzqwqx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gt2pcklwbxd.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gt2lrhifkff.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2rntxiecb.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gt2hmbjwowv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gt2ghxmjacm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gt2tuxtxzho.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwtywqgq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2pgkzuzcc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2rtfnmtuj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2xkspygga.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2thnpgsjo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gt2utnyqqud.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gt2bkhxrijb.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gt2ugqcydir.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2raezawjh.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2qjfhpiuq.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2melybocy.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gt2opbyjhpo.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2bcwlsuhl.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gt2ecwqbibj.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2wylsiqel.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gt2pmteftka.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avqsgzas.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gt2yrlnqmdp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gt2auobamjm.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2xwimhdll.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2nypkbufa.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gt2uthrbzzh.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gt2ftqngbqr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2oahjyzrh.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gt2avybmcha.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2ldvbgvwd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2khblsrka.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2ashiczlc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2vkdfkbnf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2suzrfhif.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gt2ipdzzvte.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2velmzacx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2rkrtbvzq.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gt2shciwvyl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2wktxoclw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2dujgmutj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2gpwlexfw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2luvusbyo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2tvtrpmhi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gt2pzepmwzb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmqnyybe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2jvcftmuu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2alljqnlo.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuhidwng.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkbuessu.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gt2kmrghqjf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gt2hvbcbbbr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2ifmuzxpf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gt2kctqynvm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2pydpsnwo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2aucmhjti.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2hpooylwb.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2pqdvtwuq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtwduquo.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gt2hwdadgyg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2drjkdqwt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujirgldq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2fqrcgqhk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2qklafmzp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2lylsnuqd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gt2hxrfjfux.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2tuvuocjg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gt2asgsvifv.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gt2qeahikeb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gt2rkxmesnl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2ioybzfvg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2ynqrvwwa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhwuxvwr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2ysdtggdr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2immsuuwq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shuphyhv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2jwcpsevm.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2sqdabvad.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2mhhpsenp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gt2lfcstgrj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2ffwtilhg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdkdznwg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gt2cceabrav.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2mzvsoaxd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gt2ncwuxczo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gt2rgqzfepw.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2djeaowne.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gt2trowglpf.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ikyqordy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ghmkstrg.html


<!-- 参考信息 -->