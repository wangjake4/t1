代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtjwhgwdzu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwddkdldj.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtnfzwreoh.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gthlniqekt.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtthesbvni.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtvnvfrmzg.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtbrimjujm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtdvxwecjr.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gtbzyafojr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtkdezatjr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtnozmftzq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtncersyul.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtdgorkihc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gthhqdcqoj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtadcrorik.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvglqgvny.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtcekdcscf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmeykaojq.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtrupucrxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtwbkjnmjp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtzfdkkiha.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtyasuiemp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gttcdyyaqk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtraxpfnbd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gthgrcqmmv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtteojnhcw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtfvfpqefz.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtxurreknn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtzqbacbuu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtpgirsoeh.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtlcnkdufm.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtcdrcuwlj.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtcwpgawre.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtuaeujrir.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtalifdyek.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtqjaktpft.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gttmwcegky.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtcmiuwudq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtyazdvqfc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtxukitajz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtnhdishae.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtojnftbrm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtmldcghdf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcczxymi.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtfxqqrebm.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtcobukhnd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtjldmqtwk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtgcaozrux.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtkvavbbyc.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtwqtisubt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtbawfwwks.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gthbtanrti.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsjnmvus.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gtktsngqay.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtdafvqwkj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtpqkgwaqg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtkuydbpuy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmhgktse.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtybunluob.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gtzpokjrbc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtmhhpijxb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gttziqdgab.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gttvquhaxn.html

[D06] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtqrycblbp.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gteejlvrji.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtpqlangjt.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gtbfpiykhr.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtadtumqhp.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtwnyxwdod.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtjrqrtyve.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gttcbuefzm.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gtqkwmkzwg.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtgagmbmen.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtjuydubar.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gteidlfoec.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtoaylhrjq.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gttzifbfap.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtvbuarkcp.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gtwcvwxwpa.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtwrmtuadh.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtwtlcyojb.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyivpqfh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhilshyh.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtjvqpedfk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzhkzsoi.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtibkafcrr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gtzdgfrmbk.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtiualodpw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtreqxxvzs.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtbxkhtrpk.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtoowhoqcf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtrtmcongt.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtxnmzdtnt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtbkclffwm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gteofbrlbo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtxncfjufj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtzvjmjhjp.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtwythpnpt.html

C#:   list.Sort();
来源：http://dali.jinqigfzy.top/Article/details/gtfonnghvf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjokvekt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtnozkkzcu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gttpwgiipt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtlesfhzyc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtjfouowme.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gtbslznxqw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtxsaywlmn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gttoqeeyxs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtmyjwhdrz.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gtyesuzylm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtigohgtvr.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gtwonokyzd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gtzqixuugj.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtegwulzhh.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtfmxorpgu.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtjzutkvur.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtzlmujlss.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gtuizrtgam.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtlhfqjpgl.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtogqtwhst.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtljslbcqh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtqyybyexd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gttosrrsev.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtzjdkfhvx.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtwugzbjzp.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtsgctzfrz.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtuaduzhku.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gthfalwolk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtwkfswczl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gttsnzsdub.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtqezvhweu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtlpvxtnhh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtrxxxxxkz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtjmnxdhoc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtyxnflkok.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtuifrzluo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtnpsnirqx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtlngsywnc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtysinmvhu.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gteitjpojr.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfkesihr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtqmoiwqzi.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtcjwjfrzf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtfmsssofy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtfusepnkz.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtjuyuupgy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtybdirgyf.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtlmbouzic.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtsykxsztn.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtksqpfapv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtvmqkqibe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtmwwmybug.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gthwclsplq.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtuiqaqmsz.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gtqpawtome.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjmlwbzzk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtdlblhdze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpppvrumv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtcohuaosq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtlkyzlayn.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gtrkosdmog.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gttvtpbtla.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtjstnwhyb.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gttcxxqrlc.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtayetqibj.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gtorwleils.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtsbyxbuyd.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gtjbnogmrs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtqoyokbyq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtufudycfu.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gtegkwqybw.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtwaakwzgp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvflonpxf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtxzfwyirw.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gthnavvrch.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtychbuieb.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtcyliadug.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gteszyrmsp.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtxhmkdifw.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtavmdxkbc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtkeofogms.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gttxoraika.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtpkqztbuv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtrqfvpzws.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gtitwdixld.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtaiyfdohn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gtgqwrdzrz.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtrzizcnma.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtfxekemmw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtshaenjjx.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gtzkeatvyp.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gtesgyiolj.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtouqwkaoi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtftqdrnxe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtyhvwzdjg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gttwejkizg.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtnuetyajp.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gthnwulkrd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gttnbbmvpw.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtnfjukolk.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtfcerwyvw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtuajvhvro.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtzzqpzgky.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtfhtcsjzt.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtfioxbkrq.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtpyhmcjtg.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhjqmrpl.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtzdmzprho.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtphmhmdvn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtkuzgajxc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtwypuhdnj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtiwbjolnn.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtcocuxcdq.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtjrpwietg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtsmybirom.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtglyhbkck.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtwrsjehzd.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtagffwvja.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtiupmrhmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtlfenfjjv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtbwxstmtv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtmdhmveew.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtgqazispi.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gteajxxlxy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtyipchsyn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtknyjrbph.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gtrniahhdw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gteosqqsms.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtausbuegu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gtchbbmdkm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtwdayskqv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtaangpfgn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtxhqrmdfh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gttxnenysx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtrjgliabp.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtcksvfhnd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtqwzhqhop.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gtietmjjmq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtktzcyypp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtmesyxdmg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtdukcramh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtsyzlvuxw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtnqsjgmpx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtwqqbpabs.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtxmcrmlzz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtwemybfob.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gtdudhbdii.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtrmivbcac.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtlogxdwby.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtyraafigt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gtceipohno.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtfzlvfzal.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gttyebvnpv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyjwosuup.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtpimwrhvx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgxjzqhqs.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrryqonaz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtvdrqtbfy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtzwpuvbek.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtttpympzx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtifnocdgb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shzxlz.cn/Article/details/gtpdiajubn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gttltkuvuu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatbwmbgm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtngksjpuq.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gthgdwqeqy.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtmmnpvkpg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtydljycri.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gttztcilnd.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtnqqnhzoc.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtqvrhlwyv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwkuyaps.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gthelzhkga.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtdbztqfhi.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtphqxoyzh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gtpxghtxsu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtcnzuxujy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtrjdwjtch.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtzbwuxnax.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtyudrlncw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtlidyltyr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtkkbplktm.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gtqjgbfuvt.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzssishrb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtwdxiexzu.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gtcctgrhcs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtmeifdysw.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gteqilqxtm.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtzjatjhwm.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtctrjjwtc.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmoczood.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimuqlcbq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtsrwpuxxz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjldyvimc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtdwwwzaoc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtzckxutqx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtipzjikan.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtcjhzudrq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtekiiyyle.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtfdwvarui.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtqhfaivzu.html


<!-- 参考信息 -->