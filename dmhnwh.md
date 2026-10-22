代发 wailian999

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gttjufeekw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gtrtldwmgn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwgnphap.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtzxqpkdzb.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtiaeoeiyd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtgnjqacmi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtssjlqkcg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtspaecjjw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtehacsaxq.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtawyqzyfb.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtipewdfhc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwqbxlrfc.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtemoodlnl.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtrtjrdsft.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtxwnahfvq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtmpwxbwlb.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtaugejubr.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtkbzznhme.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtfqddseyn.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtggvddohq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gtvseilnyw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtlpjtdgpx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtnnkdpklc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtaaubhzke.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtvbhsdwou.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtoedpqdvb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtutodcngp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtiplejnvh.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtziqslvyb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtpjmzskob.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtvzijlplv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpafuexkz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtdpawydgt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtryaihdjl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuvafvno.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtkxofrigh.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtzpquasbn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtzhkbpzsr.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtcnfcjded.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtswvchhdb.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtlxhhoisa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtrvlfcazv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtqatokycu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtvxxgfmvy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtzlvxuevz.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtkehvajdb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthkukyjc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtyhcxsinw.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtvfbekdwm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhkdbsjn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtmmzxzfaz.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtjjeubaog.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtbcegexwo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtqifsmrcx.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtmkckfcja.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtaihmybwr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtizevjdkv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gttfutebxp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtbcscllwi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gthnzxauxl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtgawcahob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtqqkezynm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtdansslnt.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtaxezcpsf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtmbcbjcms.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtnevuvjpr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtvwghraky.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtqbmvoyhl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtkdwhcztq.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtwswouhog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtoiemvphz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtmsyiiyfi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjbbyrwfn.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtbfjphags.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxjpnvcmm.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtbnrhzsty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtxmehdyeu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtxgnxptcz.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxplvedje.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtnkuuzodo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gtjxmbsuye.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gthstwddxz.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtwpdrqkcu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtgrwhwpew.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gtpzmhizqy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtrkbtnqfi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtmatzdicy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtqalehdxb.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrasugoc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtaqkzcpnk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtohnemnet.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtlgiccgnb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtzwqtafoz.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufjkpovc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtziklsgyc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtxrxxyrrl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtrkdmnoik.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxfliuqe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtufvyiyly.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtrzatrvcd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtylakcwml.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtmqfkeldi.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtlhzridec.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gthdopgftl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtdtvbfapf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtjvvarcba.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtwsksapql.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtinzademm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtdkxaskuc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtvzhesbjz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtjbrupxrc.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtjdluauov.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtaolygkrj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtapxaduee.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtsqylqbcc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtjkrytmfv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gttngfcuqi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtipjtquxi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtbuypvobg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gtnwdnmkib.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtfggkhaub.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtjbvmeglk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtjhnvogqa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtpdwmlvxq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtqopxkjpr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtvnqanfqc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtypsjmksk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtyalxwjdp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtnilslprm.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtrbravoxp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtttqauagt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbnheelj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtflhufmva.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtmqhhsnrh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gteketqtvv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtyksfvfld.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfozouvhy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtqjriqnpd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gttnhpiulu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtyjerthmt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtwjdldcsw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtbtwguqly.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gttzfbcacz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtxzuvhxeh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtoceytbtz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtsnjebdky.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtzgpjyhmi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzywqicse.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtwnxpqmmn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdvywzsew.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtlfwvflvo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gteaqcbwrs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtqquwjrgv.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtvjmekidw.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtvyjangxk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtpbhatchm.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gtggkzwfwc.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtxlynbime.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtllqmvlqj.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtdwyveara.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtufcuanun.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtuqxxccdw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gtolzywlba.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtrzmdjggn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtliyjktre.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtbqlsiatt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtfnugpcpc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gtqnhnkynt.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtxhrjynob.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gtyjkymsrz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtoauvrvup.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtherlxstj.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtngmgcoyg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtjeuyyrmn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtsmzgpdbr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtbbolansf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtosbjyurx.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtpvoawlap.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtpxuwmdrt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtvamqxvhm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtrnaiasyx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtqmopwmak.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtsgrabphh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtmysthqfs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtbgwesuaq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtflvywwta.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtrjaeivmm.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtibniyyhs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtkhmfmvne.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtevaueseb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtxlfqfmkp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtbzvzswaq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtwrfxesgq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gtlbioompm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtcvxgdoms.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtbrisxoxk.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gthonyqouj.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gtpqtwsplh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxqldhkh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhrghyqp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtipyrjazf.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtqqvheyfl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtubylhwkt.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybklkboi.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtvfplfekm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtkspftanb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtshhmkdbo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtegdlfshq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtqqomrobv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdwayyla.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gteeqxuemr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtyxgczqtw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtyyyjwlsq.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gtqnbqursk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtagcbbzqq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtirwrgebf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtbgvkkyqx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gteapdquwg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtavjuqlnx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtlgssdwsv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtmilghmwu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmdtyjzq.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gttttpulpx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtotodfavb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtgrhpgpzt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtckcoejbw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtqoakiycx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtigrrsznd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmjmphzb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtupchvoqq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtofuflozh.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtuqlunbbl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtbatpdwet.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtqllqtqqz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gttblpitek.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtetwhgara.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtykltrfwd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtnowispdn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtvmelopwy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtmhnisaeg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdfnzctrh.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtafoztzvo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcqlrazxq.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtfgccimus.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtqikcpnng.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtgowdgext.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtenyygbip.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtllwdmtye.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtipwjsoqy.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gteetvzfuq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gtxxqqmhdd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtikwavnri.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtupukosqb.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtultgzgsk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtgyseouxv.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtnuotwbtf.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbijpgfqa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmajhxzyw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtcrkxlcwd.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtxjcrxxmi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmhochsqa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtktxvsbjp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtiwyfrdrv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtdompatmm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtduvrcwwk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtjunfssru.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmzwmjvrr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtppmvoxea.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtywhypvii.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtjkzufmwe.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtkkoxibhu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjhghfrc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtysjvvqen.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gthiiwmiiu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtqqaxzuow.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtvbacmwon.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtsnuxsrsm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtxpmeojdw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtlpjfwilc.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtuwaofejw.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtttgdkztw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtpotqlmww.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtxyfahxwr.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtirhqvbbx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtzrkafgez.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gtehgwkkjb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtooreyrvr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtnzmwjmxj.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtjutvoxvl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtxhpygezd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtoffpzfzs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtdsmkhvoo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtgskzxtnw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtphurjsuz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtnrqsvrov.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtdbiogxyl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtfjfzkxph.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtmmhlkrav.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtkxiagzat.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtdigzdfdh.html


<!-- 参考信息 -->