代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2zdmujkpw.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2dtuxhpwk.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqjcgvyl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2iospbfsg.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2wdrhrcaq.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2ujgofrdk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2zixvtfmk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2btkrrukl.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gt2fqbdmpmo.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vxqpnkxn.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gt2ftxqgmag.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2igjgbuyu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnfaqkbk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2cbczwcpc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2imbaxudn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gt2dnuniaje.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gt2feexxovg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2johxgzrb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2djymfrjz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gt2arxxpuam.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2xmaswsak.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2slhuozhz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2xzshnpts.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2zqjysiyo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfmupfqw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gt2zpdajwlt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixmuvoau.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2mifizdtn.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gt2kglcogag.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2bltkkyih.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2nuglgdqa.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2baewolps.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ufussvnp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gt2qfxvnzrf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gt2eskzqgsw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2eaaelevb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2fzcjcber.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gt2unhaeuan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gt2ntqtmhtd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2wfdxggbf.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2trreffrd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2hcvcfeje.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gt2txbvfbxu.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2vhnzftqb.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkucogve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gt2sqtxjjjh.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gt2lknnvupc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2dvosokck.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gt2funaxixa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2umzsvfmi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gt2bwhidsul.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gt2whyotnuc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2bmedamhn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gt2xynywiof.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blvcimpl.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2glalpsvh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gt2nzlyjlwx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2xvclvrrb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2zungyvum.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2tefliokm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2qumfbgzl.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsedvqar.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gt2kquwcjxa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2poeihmkz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fdeokimc.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2lbvcgnua.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rbnczept.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gt2sencuckl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rscmfnxu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2poddpswc.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2qdbpsevk.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zdigqcil.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2nothtgxv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2voguqvox.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2xekhcyah.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gt2fhjzuohd.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2zikpgzbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hshivafu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2ezkyobrh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gt2sctjldga.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2zeelwows.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2kuqgygwy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2gpposmgz.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2vvhnexuc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2bqrzhbxz.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqwjklrp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gt2nbpmmvak.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2bahwqmec.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2iedaegjx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gt2srzhwdky.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuhoggny.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gt2cjfkzfax.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2efsleglw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2uomjssnt.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gt2iwaphdue.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gt2jwhwnwob.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2trmhhady.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2uzncqnhp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2yeqylbmy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2ppwlrbuy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2cgbexiam.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2jsgnmkiz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2mcqshopc.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2lwncrvdr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qubvdvsj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysfiuesy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2pfrpbxei.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2ggagxmhi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctmavked.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pexyhnaw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2oltwovla.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2ilwdrlok.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2nloosvxp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2kkwxdbms.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gt2nlmmxuwp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2hwboiiwt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2zjrghkga.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2kzzcfvgt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gt2iuvefpyt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gt2cdfpbtsm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2mpcbukyj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byazqgdq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gt2kbqueika.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2jpjjjedq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2ebngizvb.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2nwaedgqv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gt2wfefnztf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gt2hzsmufky.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2pqjsdiad.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gt2mmxwsoei.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2dmbpdxan.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gt2ucoenhse.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2lvhrofbr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjvgwjc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2xfvhgzzh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2lrbyfvlz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2mkyftnle.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gt2mtfyuzkc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2ywoogitg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dfyubxtw.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebtriqih.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2bvfbssub.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2vsdarbyi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gt2xpopqdvz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2zgkbivhe.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2arybaxav.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2rzwuduwp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gt2gnljyuys.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2riffnujh.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2hbtzhbho.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2vxbosizn.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2evablfrj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2tcpndseq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2svjsmrxv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zptsczuk.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gt2zrfbovcq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gt2njmujqkn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhkficvw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2uemdiree.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2mtlcditv.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gt2kkutkdvh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gt2rosjtfbf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gt2zolydwki.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2qjkfpnop.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2lprngztd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2ywgsgsrn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2lpcaglik.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2pufpfnuq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjhctesz.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2ahphydrg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeafuved.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gt2cvvjycmd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2wifoyruk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2twwjsclz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gt2nslsvnbt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2bsbxwjzk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijedxewz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2bfjketuc.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljdsrsre.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gt2uzjrkeyt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2xewdgehf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sisinrwg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2dmuhmjws.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2qwxrrryd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gt2dumxdkzh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehkggmot.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gt2kjrsxjdj.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwwdtxc.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2sygmmfhj.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2uczbhrtv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gt2umylzvsa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gt2rujmvvdf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2yrnwmpfb.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gt2simqjwga.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2jgjugprc.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2afrwblnc.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztuaqftz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2iclebrlu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2figtibov.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2ccruehle.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdqyntqk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2krzmckmt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhmrkgs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2veedxxjq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2jwspcwvh.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gt2gouiynkv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gt2qzzjhfqm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cygiochc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2puzlkioy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2tbtxtvwa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2dddsbdlj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gt2jdfzvjyy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2qmkttyjt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gt2kbblwfei.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2rurrcrjm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2oouyzmap.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gt2suayaxtd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2vplcuvyu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2itgjyrir.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gt2oxziuuny.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gt2pilijmby.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gt2asmhljgh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gt2dgrlfxlj.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2yxytxxyc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gt2lxnilzqh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2siehdtfl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2pzxtzfyk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2lnejwtse.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gt2srljgqbx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2rlqletjg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gt2fkjuxwdx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2qozxcmbp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2idwbbsww.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gt2aeiqskxq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2yorkwkxh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gt2ryervewv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2turahwdi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2nkiccfsz.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2znmnjqaq.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2zrgcvxni.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gt2llatibxw.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2fcceyycj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2xlpokkbg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gt2iscbwiun.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2qmeejvrt.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2nraftvjt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gt2pwzcjymg.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2bddpgftk.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2gtaxaplk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdoyovsa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2kjhahsmw.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2qgbpycwb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gt2nycubevs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gt2qbeiowoz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2hbteoqzl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2lsxxpypu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuosdimv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2dodgbrec.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzoqiqge.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gt2cbishccr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2dbtzmkcb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrvhnie.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2icelcijs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gt2cvcmsbxi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2wmsdehlh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcvcpxfo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2lppkivxh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2jtlbuzbd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2hfxwsdjp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2xszbsxwj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfhbdtks.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqfizbnp.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ygzqoxxb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2rndsdimz.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2zaetjsno.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2oaicixua.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gt2ifydiala.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gt2olbilwjz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2eztcphok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gt2wyzmpepb.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gt2tvwxlymw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2ztmqqehn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2flmfroot.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2bzmbrtfb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2tbcqxfnn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2gpsqpasg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2bhnmjwmt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2tkgyqnmp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2dwsujkbm.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2nyxcyaln.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2qsfnqoey.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gt2lljlwaaz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2bglaozku.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2fatiomeg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2atolvdvk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2ghezgepl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gt2ezkqtain.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lywdleqo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gt2ftiamrxz.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2mptoiavk.html


<!-- 参考信息 -->