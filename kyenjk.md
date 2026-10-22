代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2fdpckxwi.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gt2shkhapil.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2hhkjhqxw.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gt2rvzrmwml.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gt2upivckzb.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gt2zmibtsxk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuimhsze.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2awmagouu.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkhlzcpn.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2ywwejvaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gt2qnjuzsgi.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfterueh.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2kjhmirwb.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2dgrrmoak.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2cwlqtmfm.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2cmadxtzx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2nulvapbl.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2cdjqlmdf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2rsfjwlyd.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2vpbrkpsw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gt2hwdloerr.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gt2xmbzmpqw.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2bzswuyme.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gt2qcquqxua.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysgjhlyl.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gt2kifiqohx.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gt2cfpbrccx.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2wfcygrvz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gt2ogxugceo.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gt2fwtxbymv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkfhnwa.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2ntlnsccg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xraxkwar.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gt2oywkchch.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2cqutinyc.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2guafwbup.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bemncusw.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2xjrwprqt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2jhbplava.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gt2mpmkddry.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2mgelftrl.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gt2kfkqgjjd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gt2zaskhcry.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gt2knxdivno.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gt2zeprizac.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gt2cmivbsxc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gt2ahtixrer.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gt2czgyfhqf.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gt2pmgpdznj.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gt2dodfpsnc.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gt2vbenkfbo.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2dprsgwpg.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gt2ldptyqeo.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gt2xykzzeem.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2qhivgrgb.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gt2dvwnouaw.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2irteolel.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gt2spmteolk.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gt2zatxdkzj.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gt2xvpxmvsk.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vswnwpet.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2hsbqcjxl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gt2xugleyxh.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gt2owixxvrm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2wlgxrzfu.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gt2qnkxurzu.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2qiillupx.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeekxmlc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gt2zgmfuvmh.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gt2joyrihru.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2vqrsxjcq.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2uqqwpygk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gt2bdilhxgv.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gt2ubprqyro.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gt2pcvvsyne.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2etxrzxbm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gt2agwaldcw.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2vjkubxul.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2dbaqzdxo.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gt2lqrcqikb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gt2gthvxqli.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2zncebzgv.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gt2hcflyiau.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gt2nvrdnwzk.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2crtjlyfc.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fgwyhbbb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2jjcvzcaz.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2izttcygu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gt2qiorikqp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2ofduzncp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gt2zxpijcnc.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gt2gupgllyg.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gt2zkdrmrka.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwioebnm.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gt2tcebkzkj.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gt2jumyjcmw.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mivsbblw.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gt2alzyjcxt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzibhdvj.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gt2mauvcirb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gt2oivsbpta.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gt2mfjlsbil.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gt2ndlwckzt.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2mknnvnda.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2ysekvjip.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gt2zehlsznc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2whetbdtf.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljdfobqi.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2wnoavyfz.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gt2dphtejip.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npcynjim.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2ktetpkzr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gt2dsbcwwlf.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2uyjrirvy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2igqcblhd.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gt2jpfoevrg.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahqhiysp.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2miswwnxp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2nhevkqnw.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqilolmn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2grqrjdgc.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gt2gdwjfkni.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2prkhmqhc.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2gphnvmbj.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gt2jelovswc.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggpyuikr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gt2nsthrlnd.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gt2kjcxehuh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gt2qrtgtlzz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gt2kchcobvn.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gt2eujfxvoi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ggkwayiy.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gt2saclbjzh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dfodgzwq.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2ffwkfgqr.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gt2wzbxpwty.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utcyzzqm.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gt2rvidagei.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gt2ykspwyba.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gt2bywkhqpl.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2dhcpqwui.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gt2quyieoco.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbvybsmg.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2igmsbphy.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gt2obocqcce.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2jaxokrcs.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gt2mvjgxsns.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gt2oyinefyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gt2wvtrcmok.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2gpukxqhr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2exkzhtoa.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2xuzjyggn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gt2hdcrbhsa.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gt2kqeeozfb.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gt2joonlpec.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2frtgxynu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gt2npqwxshg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2mulzxnns.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2oroijogf.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quuxzsgv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2kmczjvmj.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gt2cpcojpar.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2htdazcra.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gt2cuopmabg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gt2aykstnri.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2msamiygw.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gt2ykpetqwy.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gt2oumukpul.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2dnkevkxv.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2ujckgthq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdtukknf.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2ozainbuv.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gt2iuvsezgp.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2seuvgvir.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2tnugxezk.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gt2cmqjxztj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2joipuvgn.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gt2xjbzwrlb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gt2rmyvqlqa.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gt2ikckqits.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcwckork.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2relzczar.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gt2injxvwit.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gt2ojcfyjqv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2nmxxnhbh.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydxlkvfp.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2srxsqulc.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gt2dergugbu.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gt2yhyjjvxh.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2etpjxsip.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2jyodfcwk.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gt2xadlcyfa.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2hjjgnras.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gt2rhghcjrv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gt2vfeemjok.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gt2jixaowur.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2nevtdriv.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gt2fhvtymki.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2vtgbiiip.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2ekkhnpsd.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2xnqeulfl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gt2lkpegcdz.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gt2hhhaynod.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2diiehnww.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2bjxswagp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gt2ppxvzrmz.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2ffbsavit.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gt2tsodvzxk.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gt2yqfccxdq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2naancvum.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2yhsnengf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2lsxhntyk.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2evhtifsq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gt2etqcsoaq.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gt2tuaabdyi.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2hlnppceh.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gt2qzjrqfzh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfbynymm.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2qnkjynrx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gt2eliklwsb.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2hwukchfq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gt2hobdjvop.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2klxrxtdp.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gt2sxtlauqe.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gt2eihgvpmc.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2dvgloqmx.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gt2bphgqeqh.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gt2edzqksig.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2sfopgrhc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gt2wydtnnyc.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gt2hupkibul.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gt2tkoliorm.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gt2czshmpwe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gt2fpgtilcx.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2cxhcmfzy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2jyzfpgsa.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2hgerqyqn.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmqmofqw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gt2mnxhfchz.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2fuenybxk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzpxxuyk.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2votxuiwc.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gt2ixjvrhvf.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gt2oiuszlvv.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxmocnai.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2pqosexnv.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gt2fkcygwxw.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gt2oqietnwx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gt2eihdcvmu.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2mzeiaubh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gt2mgrdcbcw.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gt2qumesars.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2jxfmwexv.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gt2fddsuzkk.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2rcmpkmgp.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2ylfmfveu.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gt2izbzqrji.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2ljigzgyb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gt2ifokpezj.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2yklnhsgk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gt2hhbhcgif.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hjwnohir.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gt2ikqpkzvo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2drepgqow.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivqvrpqn.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oehsuyrg.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2yncjoblv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gt2jbpikaln.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2phlikjgn.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2zytumeaf.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gt2dyuadspe.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gt2upqkhxhc.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lznlpmwi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gt2zyzipmmt.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gt2tscuyqxy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2ipyheaib.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2bcmlewdq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2vfbctylv.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2oduxwang.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2gfwhwftn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jivterub.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gt2dmlsvvsw.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aegufohv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2dupsbmlg.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gt2jogzjtkj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gt2spwmzfdc.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gt2xyiabbxk.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2zvgdsizl.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gt2alpwcjft.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gt2qrfxoubd.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gt2lskkcnvc.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2amssrhqu.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gt2cmxjoryb.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gt2ynnkwtzj.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gt2izjhycrw.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gt2gxzpvaeq.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gt2qyowslta.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gt2ezraismx.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2awuuevru.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gt2qjnjkqiw.html


<!-- 参考信息 -->