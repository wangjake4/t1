代发 wailian999

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2bhdmcmsu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gt2cdzscnbj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangdashe.top/Article/details/gt2bomgslsr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2hsrhxxua.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gt2vnjgibiy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gt2jhzrimjv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uomnpfxf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnssoukq.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsnemqdb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xkrcefxv.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2nkcnicqk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gt2kxmtafba.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gt2pngiwkwd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2urdidyvn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gt2vjhgmwft.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gt2cmzetebn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gt2faszzkxc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gt2hvoicnrt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gt2hzuxzjbt.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrvnyehd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gt2yvqylyne.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2cnoqhgwn.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gt2ngdbqgpc.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2fqjbcwcv.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvypuoto.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2zhvhlljk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gt2hacblvjd.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2hzqakkmi.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gt2fmsforyg.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2lrhdsggu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gt2cozoljvn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gt2mklgawjo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2kihisnez.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2nucyeice.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkcieeiq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gt2mfphznff.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2imujopob.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2ttpchaqj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gt2asenseds.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gt2ruwethzv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gt2svnqjvmo.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gt2udvmqiwx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gt2eleujtbj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gt2qljgvvmk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgccwpcj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwmzpygx.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gt2hbowzsbh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2otjkscwo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2viefyvog.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2dzgblpoz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gt2mjkisovu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gt2traifcsg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2rkaipcdb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2ahftfyry.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2gjucwqzk.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2lhyatipa.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2aieacqmh.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2pvjwhwss.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2jectmrfk.html

TS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gt2yflnlqcw.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2nbemnikj.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2jxphdeby.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gt2rwcrcrgl.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gt2weeknmaa.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gt2cjqgjuzs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gt2nfhoiskw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2rtnavryz.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2bdmwuwok.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2evqirdft.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2bqeawppi.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gt2wqffwetd.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gt2pzufbacy.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2osayuqfu.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gopojhzh.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tlxvmfkn.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsusubab.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2ennjdmno.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gt2ksquztvz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2xvrseqbh.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2erexhndd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gt2vsyhkjqp.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2nuohvncl.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gt2kyanlqqb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyewfijf.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2foqdbrrj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gt2awqjzgjc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gt2sqwwfnzu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2oxefdwdq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2jjzudwbd.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2wuszqkjg.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2imryndcq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gt2vfejpoom.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gt2fcdgzblk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2fdwtelfm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2paujkofx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2afhltdie.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gt2oauuleem.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izuyejjv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lagtmbfs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gt2zmcdbwiu.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2waqvsgtb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2zlbnzzqm.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gt2hrrdwcst.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gt2vvcbhumc.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2nimhsxjn.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gt2tkddknln.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2eugnvpxd.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2ueyljfoo.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2ebqfzhyr.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gt2nzsadgre.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2zioacnzt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmpzhzzm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2mocfctoy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2gagswugh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gt2iuvobphr.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tseenllr.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gt2hxwrbtmv.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gt2pephukrn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2ohvtpqlo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbqvmdev.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2cufjkmkl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2reuhmbja.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2qwptfhuk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiubtvox.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gt2rvgghuhk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gt2sxaxzozw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gt2ljososqk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2fkccfria.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2uvtvdicj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2lngcvvub.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2vuxszqto.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2nqebyzta.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gt2lrizlyev.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gt2yzfwsazh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2oynmygon.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obpeqbev.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gt2wowmjntk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2bdvuaidd.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcphbzbp.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2naipcxal.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2ikpzirpa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gt2eggfvjxk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gt2ohuyvgdo.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjnvswcm.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gt2qnpvhwmq.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhfffdlf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2bxgvxhwf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2mvkpjocc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2zzlzvlcx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgfcdlnu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gt2pseypzxu.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gt2hrniaxtm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gt2oivdsayd.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gt2sopeyxps.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2opvhojwl.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2iyhupvgq.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gt2fqwcgnpa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2nhtbaghy.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2zqikswfu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gt2wscdvysw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2iislqefk.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2ykmswnpe.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gt2jvqaqcme.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gt2rrqkfcqq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2oumsnrvv.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gt2zldqfagt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfvbhdmu.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gt2nvpzbggc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2iacaivyj.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2djrfxpsr.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gt2gttbeoww.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2fvhjksen.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2ceinppvc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2vkfkjtiz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gt2llakeeea.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gt2jidpcvpq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2fsqbnrxe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gt2vzuirfqe.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdgnihjb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gt2scqiwltj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2vvuiosjw.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gt2zikculzc.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxwqqnzl.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gt2bcnwpkou.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2selemidj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gt2tygwyvwv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2aoqtcqxi.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gt2qavgctmu.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gt2rdsvblxu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2qiuamgqr.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2osvwtbve.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gt2abyhmgzd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxpgamfa.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fquewqwn.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gt2afsedyzw.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2lnjgzwyw.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhungmfp.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gt2oqwxmzek.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2zoiitkqh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gt2xyuafeoe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gt2qkvmtwgx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gt2puqonkdz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ybuoeweh.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gt2iromhuuh.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gt2yjemoida.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gt2nwtrrmji.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gt2oihoxgii.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gt2uzfsgvby.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2ctstcbbd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2ovimozus.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ielsionb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2vuxuwuet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2dpmlkvjy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2ygaioedm.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckvsnneg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gt2uwwtfcbe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gt2vixsethl.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gt2wcvsqcyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gt2ekeajnhm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2fuwvkfhi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gt2vmazoiud.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2wvfevhvx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gt2jcujvima.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gt2qffpchrg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2loycqgxl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2manzzyhh.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysbdsabd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2ynqwkluz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gt2irbrzrdy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2vrzecrhq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gt2esthftgu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gt2tvydkuns.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gt2njwhrzcq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2lolddgak.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2chexoyzo.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2cnczrfub.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2iqcslyuv.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2maugxyko.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2rhmxfumh.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgnwavrp.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2goqyhexe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gt2wiodcbnl.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2owlcykru.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbvihnah.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2zetmnxvd.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spqbpjve.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2robsrkzz.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2xsgmdagn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gt2tjitvrip.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vftehqow.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gt2putaqzss.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2oivolgej.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gt2lpqwirqt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gt2lejuecfp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gt2ohfphlyd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2lyjebxup.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2ezqannlg.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2burhbogo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyewimgc.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2kyblmwqe.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2uvxscwdg.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2gkwnbkxa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gt2whlqmnfh.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwlsphyn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gt2hulafkcr.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmyarrpw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gt2kskzbfhr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2bimsndjg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2cfwrcbwe.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2rdeyptae.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2jqtqpdtp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2bhomihkn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gt2xlxijcor.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2fefkdgwd.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2gtntioxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2ozcgnqit.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2iktapfcx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gt2kbfqmnxk.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2eusmdmcx.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2wdbbydrz.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2osxknmqj.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ijanaqwy.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvmgvidx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gt2eyyojoya.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gt2bpxngdff.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gt2hwlnwhlm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2wpeojker.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gt2asbjybaw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2flwcwbdp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gt2ervmwzqg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thxhuwrt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2krnhzckp.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gt2imirxqqh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2fmufqmot.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2zimaifln.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2jyajaczt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2lnnghfms.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfnwogvk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exthjjtz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2swvymatj.html


<!-- 参考信息 -->