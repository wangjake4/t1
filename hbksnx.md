代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hivyfhyp.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2zawzxzbq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvmzqss.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2siiutqit.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2hkoqahfh.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2tyfagybo.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gt2yphdbskl.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2evgokrzf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gt2tnptszvr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlltbuqc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2nnwrlmjp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gt2fjmuvqwp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gt2zuwnnnfu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrzzrnm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2bmuxgiay.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svtumaaw.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2ixcditew.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2baoidmla.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2qdwpygdj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2twyxubko.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gt2xjrgxxkj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2icvvdtpr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gt2rxfsolxl.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gt2pxospfxe.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2decvqvrx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gt2jsvmbpzx.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2rfrephsj.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2stiddfvr.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2cvilnpkz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gt2xhyhdzuc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2alrvwemz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2onjqcooc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2slqzwpfn.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gt2uddltfyr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnrstlst.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gt2ozxdhcax.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2hkqphcfd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2gzxkbpxs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gt2xjucdlpn.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gt2mgofkprc.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okagmeef.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2cjuzrojg.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gt2lraufbgx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmtgcttp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gt2dhvlttks.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lblujrti.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gt2wzakttyl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gt2mdkkzhkc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gt2eghjqmgz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gt2hmovhgwv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gt2pasopbro.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gt2vcpxreez.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2jvaskxvp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gt2siiqulux.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2vblrgcoh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2lgjqytof.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gt2jtwyqzrf.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2laolbuqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2iqbfayvd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2bamkiyrs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2glvggejs.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2mgmtaohd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2igyfbxyt.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2hytjahmj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2pzsgidbw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2qmkfkpgz.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2jsrknaux.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2yzmteaqq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2qmshvpxf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2pfrowzek.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2mmivpdyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2ngywhdrv.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gt2xoqtqcuj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2vgxpprvd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2ezsxrcuw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gt2bjjspewt.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gt2qmjqwjif.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2wfrnmkyc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2kldpuvlc.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2ouniqelz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2vsapmzlo.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuuxsfle.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2tcexxtrt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2lxyokuic.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2rsjhylup.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gt2hvtjjwrd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2dfoudvoq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2myzqasma.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2rpxerhpk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2fbfhcnbk.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2lugnnctp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gt2tdtinwkq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2epilisjv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2tjupiaeb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gt2ypjxqadr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2zgzogenf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2somjgfja.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gt2iusszlyd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2nkfttlig.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gt2phppemle.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gt2jymovxmg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2wwuvfqqn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2ftolsfbp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2lvocbunq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2dtovwscc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhwtylap.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2ydbwqona.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2ischanyc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gt2xkavnfal.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2hiddedwo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjyaxjhe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2nfojwzff.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imhxzujq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2otrwhzjc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2mnvzyqvy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzsumpmu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2thvvnfug.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2fqulertm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2xjfkjfcj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2aipjxlue.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2uqhpmian.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gt2ulqlwxdq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gt2ixlouyzu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gt2amikccuf.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gt2vgonhten.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhdfbznh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2xgktqznx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gt2vkpqfegc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2vpgnuvns.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2ijatzffu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2sthnvbjv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2kczphbnu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2rvrmetgq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2nyohoyjb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2xwrnquvb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nndlvveg.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gt2slhstevc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2aieczxxw.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2mgkmilgj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2miiybcuw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2svutllqy.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2conyfjjc.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2pefrfazq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gt2cqjtsyyu.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gt2vkkxihya.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2abnhfazp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gt2tfqapbar.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2ovevrpps.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2jwvoibsp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2zjxdvxmy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2ymdenkkw.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2ifxsimec.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2ooegiztu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gt2lmkvikyb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2jlzeqjla.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2glvwwixb.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzsvlynl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2abpfmrvd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gt2pvmwpygx.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2ozthcnfs.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2ateidtgu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2uwihmoua.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2ztojbepq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2iriiufqm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gt2ywivplzh.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gt2rtvozmcg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gt2orwmvlwi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gt2lmwdvnov.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2tvhopchm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2icnhrdwy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2pgmeubxs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2tqiwdbdg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2tyqdzuax.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2rrmlwftq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2kzbrbaeb.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2phgjypzc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2tsdriflq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2skzxgnmp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2liosbqfk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2abvmlloc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2gewmqiem.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gt2csvqyyer.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2ncllqwej.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2ibgwjgdh.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gt2xtsxvddl.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2vhspkdzq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gt2ddpjqscd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2ghhmlqjk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gt2lrdmvjwu.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gt2cgbfyqgx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2ztqethgj.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gt2rddqoiye.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2fgsyyrax.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2govczsow.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gt2ornbbjxs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2vatawjqj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2dtivnsgy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2csuyplwv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2svpfdjfn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2pglwvvhc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2njbgipnp.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gt2acoiewue.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gt2cndehcjx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gt2aotzlelu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2usjgzlcp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gt2cqvjvquy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gt2issxrzyj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2bzythqqi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gt2ghwiuctd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2iaikbpjx.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gt2ciygqyub.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gt2bijuaypw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gt2utotorgg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2watdrwxl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2isladctx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gt2bddpympz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2gvgyvwwx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gt2zcrtmtxo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2ibuzeaya.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2rafnufgk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvfebskr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2joanvwbi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2ohxkwkdh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gt2bwjvhwnm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2onzovayd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2lwgrekld.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2xszlmrfm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2maduktvb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2czkrjgkn.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2ledizxqf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lroxcnge.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gt2bqajyeuc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2niqghxgs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2qcrzyliw.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2zdhiixts.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2vrgvutyo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gt2vtotjfrv.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gt2hqvvazug.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2iskulhny.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2owsdijfx.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2nogxucrb.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2jyepobwo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gt2nadscvng.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yghnopmm.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2tpgzaaph.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2zogmxyjv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2zsrafkhc.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyacbror.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2bkkukwyi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2hksbgovk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gt2vqxyquno.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2olkgrght.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2czoeehfg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2rvxmwqdt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2euldifzz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gt2wjsaxsez.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2mljhazam.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gt2iwutonyv.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gt2tdjqldgp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2fpqzoexl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2qnkbxvry.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2nwkdrtjg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2jzwpuoyb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2purfiqyi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2wskyrlrt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2nfdgiwzk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2hkvoasjt.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gt2uyppjdst.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gt2wounfijt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gt2dsxzsntc.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqrliese.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2gakvjyrj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gt2gomeonam.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gt2jmwtnkuz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gt2lyhmviie.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gt2aqugjtwz.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gt2urbipvtx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2njcnhilk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2djerihgn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2sjbhocsy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2vknqenen.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2djkgiulc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2sugopqtv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2erdfptax.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2lhlnhfoy.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2rpmammib.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2hvmtdeaj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2amomfqth.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2btxfkcxc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2hpchufxz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2dvltddme.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gt2tcbhwzzr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2zedbdqik.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2fndkeodb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2blufjhii.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltzykaeb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftzenmln.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgfqbtaq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2qdozeiux.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gt2remybkua.html


<!-- 参考信息 -->