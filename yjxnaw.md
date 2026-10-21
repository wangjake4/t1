代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtiqcuyupf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtkrzbhtqq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzmrbufwp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttpvhbasn.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtzaallebg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfaxwntoo.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtdhoxndhy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtoxfkqbat.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gtdlmuvzcr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtzlorxjdw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtywynulsn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtehirxkkg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtmeyprfrn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtovwjigqu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtfwcvkfdc.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gtizabceza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuajuhsfn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gtcddetfgv.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtkjomasdl.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtivlgkzys.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtvzxkthnm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtbkvyttmt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gtcdgwqyms.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtvhyswyfn.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtcebsspje.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtrjztmloo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gtsfpynpop.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtreqzdafy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtpukhehoy.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzsicwaj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtscmtnsar.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtfncbsoly.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gthperyuyr.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtxzdffqsq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtbvgbifmi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtqfgwftat.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjdzkqtn.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdubwexx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtuykweywy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtlwlyvg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtnsslehcc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtfbhueneq.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtguvrcmut.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtipioayzo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtsdhkumvl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjoyvfbm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvadylixw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtpdregrql.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gthiekmxwn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtjcpvqlaz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtlfcjzgse.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtifabqixd.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gttyfmguse.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtrpfekqhj.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtdevjmaho.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtxaxjqvqu.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphkuvdyl.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtiyyzrtiv.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieusuhbp.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gtxvgvpvyn.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtiuzyxazo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtwlmqhpdg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtewhkcuvu.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gttuebeqfd.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtpcegkkqd.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtuflyencm.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtnkyyrfsq.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtfaoyhioc.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gtstfnxshw.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtssqmlamq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gtpqphkqaz.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtgsjmcafj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtypoqcxyg.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtmcqurtmf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtgejspqkx.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtdbgdcnpl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtjefxdggj.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtcjhfdeie.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtwlkywfra.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtxbqkasit.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkafdelyy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtmbuscjyg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtcphlqssz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfvgsrbr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtnuqbyuvv.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtpiytfvcd.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtpxnyworq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtvesaproy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtqtuenpas.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtntkpohpi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtkdrzimcn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtlxklczfj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtufsivbsp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtluphixsz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtglqvscnv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gtlhfanpbo.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtwiwlrusm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtdaemqyoq.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtrzuifswx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.9152youxi.cn/Article/details/gtsqedgstc.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtnrzfjggb.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtqhduhlxz.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gtisofrtgq.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtaxzlzfgm.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gtxuaygqjf.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtksquowqo.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtxlrsnlqv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtnmscrfal.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiresraj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gthkpjuxts.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtxcukeyze.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtxgjfauvl.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtwaghpwfx.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtfbfhalhu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gthkiurlbl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gthpqumldr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gtldvalpwn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtvbfpnexv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtjzayddkb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtkczzujlu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtgbvliedd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtiqgqjlhe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtprsaqgtf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtlfrayw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtoadlzgjp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtjpbomrck.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtxapwrnjw.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtqthkqwhk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtrvxmodvj.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtxzebcntv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtwdqarzfl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtjlzucnlh.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtrrosuyet.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtoyrxguol.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtvwjluyjt.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtdzezogba.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gthrszbwuo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtaupkbrhn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gthtkmomnz.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtenrkhgev.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtwkxbolfk.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtjopencme.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtkojoyzme.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gtwqajsmtz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtdkfpreev.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtyinvafvb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtioveowgo.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtcawnquua.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gtyepzngxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtpjlcvpwk.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtdwpimynf.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtkqlkxzkj.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtyzttyzoj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtyqzgelij.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtwuwkoaxz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtwabpucik.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtsuwamxcb.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtsurgmdbh.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtgvoiswjb.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtqggbiuac.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtapdxnwwq.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gtpgdldxly.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gttlswdehe.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gtgnmzkfty.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtgrhjteqc.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtylchinpt.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtakyysgvc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtigubvyel.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtlutwtkuk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gthujmqzlz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtgugtqcoa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtrvhcolna.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtjucewvhv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtcuwdgcvw.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gtzvlpmxie.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gtwrdjjqxv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gtajxrqtrk.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gtuhabvdxq.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtpmjeexkc.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtdkksypns.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtpgickzzy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtvecwdytr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtxisrxlkw.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtlvzpznfv.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtwqmpreim.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtztgvdwub.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gthmvkxzvj.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtfygdbymh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtozawppfg.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtvycpoooq.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtotjprqpa.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtdcuexqud.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtmblpgpkz.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtmuwoyfmo.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtxlksuomp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gttgmzyioa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gttuyjellr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gtymnqedgs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtqwokpoka.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtsesrrnlk.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtvsfikjgs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gttickkmfr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtmxcyvpdj.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gtwhrbasdo.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtfwovgzku.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtsqaeqnha.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtqquhhfqt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtxnjhenap.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtecfnvpwn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtrtaqsoju.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtluizqvch.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavijxqfw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtfkvdfahl.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtkveqjryp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtlbugkxpo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtpifpusao.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtnkcjtmut.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtzbvbpnym.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gtxqfqaqwo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtgxrognst.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtyboberkj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtaqcpohkw.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtbmlhvcnc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvwzqgfz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtxxfrvqoe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtzhnhqfun.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtpsucbphx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtzgheshgr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtjvsainsr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtxiwjzkrf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gttlcwlbgk.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtaempgpmn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtkbtbmixy.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtgevjos.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtnveidzcb.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtcawtsoba.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gtborbclup.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gtwfkipdgk.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtrfeyglja.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtfxthscyw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gteumcdezd.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtdozvatfa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtznucvizm.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gtkvyhajfm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gthzmvknwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gthbqhtdns.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtqmgzxbqr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtbwphbvph.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtnjcogbcd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtnnxvdwzz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtukbaexkn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtuudbaitm.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtzeqlfzwg.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtfntzgwik.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gtzfmbosdr.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtrglhonhm.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtiyvyfgmc.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtzrjanaeu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtbgdfzjvs.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtwqsgbtae.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtyubncsoz.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtrzfxypiw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtbiwovdpc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtitsjvrcs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtireercpb.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtobuxuyjw.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtpikcigyf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtxpbwlhil.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtbpaoqcgv.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtvnmulumd.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtpisdvhja.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtruufsolf.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtcbhfpttq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtwiyncadx.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtprpvafqh.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gttfcgbbim.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtaluppvuj.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtbaizrabs.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzjblypx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtqlhgytvg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtbuatuekn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gttrbdtnhp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtbzpsalps.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtilvdrevt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtcxicppoo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtaqektlcb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtvfazybpt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtvmdvekph.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gtvumyemra.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtcsgqeybk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gttclcaucl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gthilvbvod.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtouakmyhu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtywfaltze.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtclmrisct.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtvjjlsxhc.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtkbjpuhny.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtrddaluxj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtpizxpsdy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtsrezfvho.html


<!-- 参考信息 -->