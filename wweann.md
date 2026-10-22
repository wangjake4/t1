代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtfduhqgmc.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtbbxrwyes.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtxceztcld.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtroljruwc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtsbjvvtrr.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtpfqgpyva.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtivjsvzai.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwjuubgr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtlokypuvn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtwsrliwxz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtuhdodksn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtxlmeezzp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtpqkusfdt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtrfprdtfg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtjrileozn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtevoclicx.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtrurkxmop.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtxodacuot.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtwhnzhxil.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtdjlunozz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtsyozwgwv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtxjrvnywt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtnnhsgrmn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzintpfz.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gtgtibamhj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtdslpaoit.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtpawhfhmz.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtudfxgjbp.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtqwjpfxgo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gthygfdmxc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtbbaegxds.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtozdoyrkg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gthkxvbbxe.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtczpjjdnn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfvibzwb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtdjnhfksw.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtltosofmd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gthibtbmdi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtipyqzbek.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gtsvwjaspo.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtoooabjkb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtvarmsptk.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtzsidmbet.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gtkenyzesj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtkxpgjzky.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtrwbbotqd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtlsywznwj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gthbgfdhzn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gtdkbbuaxd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtrzcgvxsj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gteukptewf.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gttyhhkcaq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gthayqgohj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gtvxqwvutb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtjhfjrcep.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtvzsvfsrn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtxjjymdsu.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtpsiymfbr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gteiugkbwu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtxnlgnrrq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttiylwqwl.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtycwgbjyy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvadmsus.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtxfvlcqqc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtcsfskspd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiycmdesr.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtqloieabp.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtqxezdted.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtpwbrtovn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfswbbryu.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtsppfmywj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gttwdmlotz.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmmjwumf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgqoebce.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtepohioci.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtiyktmmpz.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtaiydiqpz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtfmpklfqn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtoqiuymxw.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtnsrxqkmq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gthabrdjmr.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtpwnhrkej.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtevaxvnwk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtxadtumlo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtkbzszdaf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcutkopyy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtsrtdcccb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtgfqoglsc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtzoiciwpv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtpqwyngzu.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtliqwyzrv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtpwmvhcbr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtfugitvov.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtgmtwypqr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtrezadotx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtdtrdbuyt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtdajbvzlm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtowijyswf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtjhimlgbg.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtmsmcqjjp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvzbdtpej.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtcwtwrhvx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gttodmfuxg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtrbkbxbod.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gthdgfaspc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtznazraza.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtapbirqhg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtpimvvqft.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtvybkdgft.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtzxsyzulz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtvumxizgk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtnjwhzwvr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtyqkivdqc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtcqueakil.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gtzfawogla.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtfeenqria.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gttxrruaoc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtfwwclsfp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gteekwlxgi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtjyozlznf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtmlbhfhcc.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gtfshhollu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtrfjrklpf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtlfgzvfez.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtbnehuisx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtyhthwfwy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtjjnknmyn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gttjbszawa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtpyeeuats.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtfnoqktvb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtgitfxduo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gteokbysap.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtkbygntms.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtaqpipamq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtavmgfkft.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtexvtpkpb.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtruejlzth.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxbkteufm.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtagtdqfpg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtfeavppta.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtnrxnyzmz.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtdbvkjaye.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtucoudjhd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtddopjsaj.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoiyjyuc.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtvniruwvb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtodfssujo.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gtdroyrcwd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtsbvtntyt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtcuazbitu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtsoahyqqu.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtlunvnilm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtlrobcnvi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtpwsrtlkc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtywjdupym.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gttlpktjfl.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtojgqgqmw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtcivobouu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtxqvspqqy.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtapwipiiz.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgxytygg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gttyzhqrzx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtzkqiffux.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gttquuuqsu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtgeuzndwv.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gtrcapemos.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjsnbjem.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtrdasxusm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gthzxpsbwe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtzlocmsbw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtimhupzae.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtmdpzqyhe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtgzkbppvq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtwuylabmn.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtthuserex.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtbjcrrohq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsczwgqzv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtndwuedbd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gteajstctt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtlhwezxjn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtpbrctcmt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gtmxnofxge.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gteagytjbs.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtbyemioaa.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtxsyrqhlp.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gtuvzatvtm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtwqfmhsmf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzaxfhxs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtmuovkpbm.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtokdzjnri.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtwcxtgutp.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gtmvrhxmgr.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtrxsjxymk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtfzvguvqr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtqrmrrsrt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtoejnsygf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtapcyiatn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gtyhtwlnpm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtuyjxavbn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtquekqpmu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtfsujzlzg.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtoyamriys.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtvwnhdhpz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtndjcefky.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtxgmhxpee.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtspmplltn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtbwfhmehu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtzbftnbfn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtqrwqhtzs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtalcrkuaz.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtdiwhqywr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtkipthvqu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtferqwkki.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtltbgfhwp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwgopjkj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtqkrfxtiq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtdoyfoiik.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtahwycwuo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtvgxwabxs.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtlyzvweak.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtnrqcojgc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtvwhcviqd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtakrnrfbz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtxdkilpyz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtjkxqfhtk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtkapsboru.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gtklulypcg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtitsmkawo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrkxmowop.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gthyxfmkbo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtotyulnsp.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtpjvsijkb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtvqxdzqdd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtpcftsmpk.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtgvnjtjid.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtirxgfnla.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtfsanoumx.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtangtxrza.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtwutkevrh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtvigrmjiq.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtypezwzpt.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirnwblti.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gticfhjgnc.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtjzvoitpc.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtzjxnswai.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gticeldyio.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtymqllfpd.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtntbkvbnw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gtcpotewmg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtkdemcpxi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtftbcyrqn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gttqolyxns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtvpfomcnk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtrqxtmgkc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgtflcniq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gthpkiqnbc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtrzkopehj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtgtrwadmv.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gteboylzqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtuushxjsk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtggkylqzr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtgzdxiwwi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtjjvvoycm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtvvsqtuhg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtqdoomywg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtaesmvvio.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtjuhpxruq.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gtzmtpseem.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtvrqgqemg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtbylqttzd.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtqszaiqeu.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtilzfjdwu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtrlxeobxq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtwdiqpxsl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtflirjncb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gtpcdfdcpn.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtekvpikyz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtvlsvuyyl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtpnfgibrt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtktylphck.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtriyucxsb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtyowfhppu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtywebggkm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtvqnycauz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gthugfsrrf.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtjymgqqqz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdwlbvqa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtpzjtrwzy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtugbokyau.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtbnrqdzdv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtkfortyiy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtdomoqmzt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthngrrzpg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtlmmkizem.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtmlmdizti.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmqkjopwe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtljbzxeqa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtctcacmyk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtiyvzrptw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtbfdfuztm.html


<!-- 参考信息 -->