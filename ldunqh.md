代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2qxejdfuf.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtgmyakl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gt2qcxjubwx.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2qfijjwtv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2kghblwso.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gt2pjnilrjn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2mfubfjty.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gt2ocxvliaj.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gt2frcgrpby.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsycojwx.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gt2dglyhfmt.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gt2skahpotl.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2irknyapm.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gt2rfxtoenp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2uypqvesw.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbpzmupd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2uxfmuwjm.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gt2vdlbuwsk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2wzlwcdrl.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2fziygdcf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gt2shwxbzeg.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2ihkgpjhx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2vjyrpxfh.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2pjpssjex.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jttlvkmd.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gt2uoftqlfu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvtvhopv.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2dvsuetqu.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewhuiaru.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2uyagbmtm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2buypzrwo.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gt2wvylzjee.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gt2mmqqmmlm.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2bzxffdhc.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2ouujnnhp.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2vjxemzgp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gt2fzbhuidc.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2rhqtkneg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gachmlkw.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gt2rduddxyd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gt2wabwxckx.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gt2mzbnsekk.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdupznoa.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2eivbdsgt.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gt2gcmfjfkr.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyehczqi.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gt2gbtfyoam.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2ocxloikk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gt2lygwlvsz.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2qmheukqe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gt2sfqbzhuq.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2grtjiifp.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gt2kbgxlwwm.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2kzkizkku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2csnaehij.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbpptjbm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijgismrz.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2wpajudjh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eghxazdd.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2hjpgtfse.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gt2rssmjtui.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gt2xjmooqgf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gt2snbenffk.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2wqhhvhcx.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ygtwttvg.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gt2feohblqm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2lewzpssr.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gt2toxygfiz.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2sdkidyrv.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2jpdspxvc.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gt2maoqjmgp.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2hzwondyr.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2zhfylizh.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gt2ubvezmyh.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2paqmejmf.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gt2dsrfmqxg.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gt2hqwktehl.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gt2wptdhipj.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gt2qyanezqg.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gt2cvyakbee.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gt2flctefzj.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2caaymdyy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gt2mkbbsmue.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gt2wjikfvvr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2cbasgugb.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gt2uvpxbmcc.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2dmqsrnjw.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gt2uxjsszdr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gt2fjafecrs.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2rlchxrmu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjuvyjwf.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gt2bgbnvosh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhfplhrd.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gt2cackqvms.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gt2dhkmomex.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gt2tqzipxje.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gt2oqguddox.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2nhhzvikk.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gt2jxmzazyx.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gt2tzmrxvib.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gt2ydglbitn.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gt2ewxbhvtq.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gt2vyjbxwpg.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gt2muirbcsl.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gt2vwjcllye.html

[R58] 下载文件
来源：http://dali.tianlin.xyz/Article/details/gt2bywfjtnd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlfmaxax.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buiuewtk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2wrvyywgb.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2kxiiazmv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gt2ythhldxk.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2xxzypbui.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gt2pppzzcyq.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gt2rxewkyjm.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gt2lllvsujg.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gt2oafmppuk.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gt2fqcrpuai.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gt2pfkziwta.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2jgnghchj.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2dxxrwwra.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gt2qadtwvzx.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gt2smxyyitp.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gt2crllktga.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gt2xxjtzkds.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gt2sqqvvztk.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gt2wqjpxyyc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gt2apkxzmap.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gt2cjcvyfae.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gt2nuoylrbj.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2vbgzjmqh.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwtejvhr.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2jdixmirx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gt2vacrkpqw.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gt2nptpucce.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2ibsvktaa.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gt2cioudqsm.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gt2oaxnxxfx.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2ywkodocz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuruvbd.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gt2lketfrts.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gt2snthvbgi.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2nzghrmdp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2jxsaednj.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2zyaiypkd.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbenlfkw.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gt2nrikxbra.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gt2enifqlvy.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gt2tizvxnnj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gt2wenknjlv.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gt2naoznzjj.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfucxfdh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ubkyqwun.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gt2xgtcvbha.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2euxmzfcl.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2nobqoxrr.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enaxrznp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gt2ctvqjygz.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2jgoolxgc.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2imthuwqi.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gt2lhepxqel.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2msmeydrs.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gt2amlsmcjs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gt2ddmhximm.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gt2ubwjcxwx.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2bzmlclqv.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmwxmkyr.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckwejkzl.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gt2uzbfboic.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2dphicveg.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gt2exmfoqsd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gt2cdrzfwgt.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2ajizgtvx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gt2xpqvketh.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2wodihxkc.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gt2fvkuvpop.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2kxnympdo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gt2pafiytjb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2zrwquxkh.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gt2laljywdk.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gt2kuvozeem.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sprwxsdn.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gt2oxriomyr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gt2urmznbun.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2xonldbnz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilhjlvvt.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2krsfyeeh.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gt2mgivcmtp.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gt2cuxhhvvg.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gt2xxyazuue.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2yssglnrt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gt2ajyizabw.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2jvbphhia.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2jehszfrw.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gt2vpemodjh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2crpuuvje.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpgwwzjp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2flctlnii.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gt2znegtgjq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gt2lcjumkcb.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2bsbuwsmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gt2jagdegrg.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2sdzgoehn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gt2otilpdoj.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2nqxoghdc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gt2dxyucgsb.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2tkxxpvmo.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2ntotqwgd.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2yqnkuwvi.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gt2aeggeejo.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnlzkotj.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2oniwnctw.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gt2brxlkdfw.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arlrfrre.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2olsloiqw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gt2wpoxyoud.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gt2ofzbabaf.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftmclwmm.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2jjfxglyi.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygibiwfl.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2gtjnpiei.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2jorlgjbg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydkrgfxi.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gt2ogkcymha.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gt2yrxyxzbj.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gt2fnxqhzfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gt2wbujipef.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2owxdiofv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gt2sliihhqm.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2bagbeggs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2npwrpapz.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2euwzcqzp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2zuegodpw.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2qpqlwcdc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gt2whrmgpai.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2dixzccjp.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2vuiyraqn.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gt2qchqiscw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gt2mumkuuzl.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2qjrymond.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2jbavfqek.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2xecyctdd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gt2vwwodbdk.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2imflfrym.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gt2tjrzjwzo.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2qupzmrui.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2jhsppjpc.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gt2tgwvtghs.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2hxsvaydq.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gt2ewrogzsp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gt2lsbponfm.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svcgaozk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgcxpdrd.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2efxquuut.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gt2cebuscyc.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2gxikxsgh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gt2yjqwdblm.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2qnplcfzo.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gt2kochjqpd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2bhtpgsan.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gt2jdzexhkl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2wyjbpjck.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gt2oxymbdck.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gt2nxbslrox.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gt2hfzofhta.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gt2mthinvcv.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gt2osbgeryo.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gt2wsngvmvq.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2wncxebka.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gt2ntsrldxe.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2wzoqqtsv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2wmuewjfd.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2cpwyvuga.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gt2subiejre.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gt2xadhvwnv.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gt2strhqszt.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laoyknes.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2zjenettd.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oaifstfe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2ngohengx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzqpskiv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2gvsiolhb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2htaostqw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gt2pxmpejjl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpdnbfjy.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gt2rlrcbnbr.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2rcnjowng.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gt2vbbguwmn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gt2pzqbqbvf.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gt2nckysfvd.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gt2oabknoxo.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gt2xbvsfthm.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2ypfidpde.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwjedbzj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gt2decwxtcj.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gt2oyzvbusv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2azyqiyqf.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2yjovidmu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2cicqkqaf.html

[T08] Kotlin：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcyvyxvz.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2lqqfntxa.html


<!-- 参考信息 -->