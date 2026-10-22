代发 wailian999

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtydwfggim.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtwtgjwctc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtaekwpwhs.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gthxdikyee.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtopnqpfun.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtasugqngq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtjqwbbyli.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtgngvvqap.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtdekivtkq.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmiisjym.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnrrjhas.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtqphdldqg.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtmyyevlom.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtnopnwesd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtanbqvumd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtvrrbukwb.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtozidgtwp.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtwfjwtkrv.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtamexbqex.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gthemylmcy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtwyqqqbjf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtiypplthw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtgxsvqeyz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtomgdwnte.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtpuhvhkgi.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtgegeiowa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtuqomiuur.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtqdkakrly.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtgyqznxux.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtunmkydgz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtjybnafeo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtuqumwqoc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtagbwegxs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzditwage.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtecpbvyzw.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtxsuovvdo.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtkjpjjroa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtxvjtvdhl.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtcpbxsjva.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtrgzqtsds.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtxiptgmlt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtvrchnzma.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtgrharvam.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtjksqqegd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtykhkzgqw.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtppzfbwwh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtlpmfqfgn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtqyexxhgh.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsncgjtrv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtijtaxygn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtwcatlpab.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtmpcmtzrj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gtmrfcmtju.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrujftwpq.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gttdouxggq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtzjbgrnuf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtypjshswe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtfqkkiebh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtfhrqeoba.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gttcwyhcch.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtnxfpxgqa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtmzjjilut.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gtolahbwqv.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gtjgbkmasb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtacnvfkps.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtebqikzhr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvbflnrg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtvswkiudm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtbzthvokh.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtlvkbrosq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtdqjwrmib.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtclmwelhg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbgbtmtlu.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtdkupwirl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtngiavfwb.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpprcrwkl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtiehqwpnm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtbipblkts.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtvmevvabj.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrfgnxnzq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtplwcxise.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtwzjzcrbb.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtyfpzubcv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtlkmnxcto.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtoouwrcjz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtbyaykwpn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gttiiggktk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtxdhasvmk.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtfoalgchb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtludwbewk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpceyzofn.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtcnvwljfq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtllrybdmc.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtyyevjgxh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtmbvoloqn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gttwkpxjks.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtpgnlhorp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtplixeuuv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gtcbfhbhfk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gtxpoypbsu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtksnxiiry.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnceocxn.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtvsbvgoug.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gtlomwgtqv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtnaflvbns.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtilogyonh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtmryxwdae.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gthigmtuhr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtpxdorhsp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gtruwjqqsy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtrmtcddln.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtjjgxgtzl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtfxnieidv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtogaajccg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtvfrjrrus.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtuixmiyao.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtitxyuxzq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtolxvfxzh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtfmdheamy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gthzfqhiqu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtvadhenzj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtqaatvyus.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtqihvygkq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtraxdvdzm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtedaiczfv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtomgprkpm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gttwbowdyl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtpyrlkcot.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtkzoovvjl.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtmvdsuabh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtlhwkfrbz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtbegxijxy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtunnclhae.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtbrslakdw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtnefafqho.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtunhiktzm.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtsvmzegdc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtluazgkwf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtzmpclaoo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtuguxsvur.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtbsryznxd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtoatligpp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtlpuwfkrn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtdroguepk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtxqbuwaxt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtphlyryfl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtajfjtgcd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpcdjyxpp.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtjetwmxgr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuhdtrdcf.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtbirznwht.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtwfenoztg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtgazdpjbz.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtzidqbuaq.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtwnlpqejx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtobuaubgs.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtlfczipbg.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtlqdjurhl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtibiuykjj.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtjwmrwumh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtualigxjg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtczynqlyx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtysrtkupu.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtjwpmkuwz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrqafubd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbnmksrx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtdwbufzur.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtrlwdlojq.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtinftayih.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtvrnhadep.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtgbygkiua.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtgpdyhhtb.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gteoocdmos.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtgugqyfnc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtzbiivepf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtoobckqiq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gtjnobhnpx.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtoujpzhix.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtlxmqenaq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtuedwbnjm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyrdafki.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtvmidjabm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtfgehhkpy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtqvilhgnw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtpnhsypiv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtjujnvfsu.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gttlmpmarw.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhbzrgbz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtkhfqbvfy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gthymyzemp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtnifmaudt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gttykolwom.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtgtomiexu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtajmipmxb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtqhmwkddy.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtsjucdije.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtkeykultv.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtksebkour.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewsbmfto.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gthnihlqah.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtuwcfplmp.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtbgtbfydy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtbnsyjdfb.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gtsncwxttz.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtbhnciopd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtwhmedrus.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtmvdazpkr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtibcfphec.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtdhvtfxcp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtlaoknvzh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtguesyjrc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtucattskt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtfpefyfop.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtutqrhiei.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtfarrkkff.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtqhcyzumu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gtocbtpmvx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtixueid.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtdruunmhw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtdaszxrbu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gthaovphif.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtbpvrznir.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtesnamelm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtemnvalew.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtsrggufhx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtycpunwld.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtbsqpydme.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtdmbrqbxj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtxowlclib.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtzdainbnt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtonxiaqpm.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtyxraesvc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtjygcxsde.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtzchiigom.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtlzibkqua.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtrqjjjoqs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gticqgnqho.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtrhhjslhf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtuksjmpuy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtezdjyxhx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrmggqqub.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtdorwfvtv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjyquwpgu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtqjvqahkl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtgueghgtw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtlrsbhjvm.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthkwuunsd.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtrbocyvsy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtiglpukmv.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtdmpdozgs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gtjmxxfnkm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtzojgoetb.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtfskcgiwi.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtewcyhpkb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtoozomapy.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtamzestir.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtxeatrxpe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtoccnhbou.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtlzdjazyx.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtlzejddxq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblispkxl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtyekragtv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gthizhbmnl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtxgznmcel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtkcgxpalg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtsnsdyrgo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtculxvkya.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtaacnxkfx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtuakosjkm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtytsqseyf.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtagcuiwni.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtwdfunmyf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtvqoozuqj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtmpacdyrw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtgufvxtsz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtczdgklqq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtxskywgvz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gttxqwbjpl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtadsliizy.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtxkbtnuha.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtcihzoniq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtmbtgkuxm.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtyyzauwsy.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqnzklty.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gtmxsjpyxd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtaeamjovs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtoucxrpfm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gthletavtp.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gttzwaqnlr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtpfduqmlk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtfimsvinh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtdwfmocau.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtgcubmrou.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtntiwpxkn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtergsjuto.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtgzbkjdla.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtjeubfvpv.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtxifrwant.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtanjndosc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvgosnly.html


<!-- 参考信息 -->