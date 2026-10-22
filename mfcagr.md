代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2bhyhpvni.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gt2mdwadblv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gt2rpkitmdf.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncwiqnum.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gt2eqxjegjf.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2kbqorpql.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2jempfuup.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2xwlxpwty.html

esac
来源：http://dali.sweek.top/Article/details/gt2bngujobx.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gt2qltpigto.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gt2ozrpwrix.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqqwceuf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2onuubqjo.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2igcgcnhy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2lhfifjyd.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2uybiiems.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2lezughvs.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gt2qregyayb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2gnfiqpxk.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvxzvlji.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gt2hbjgaofy.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gt2yazajeyy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gt2nnqdscar.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2mgmzsxpc.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tiyshjtu.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gt2zsmeurcj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2efynnblk.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2qsstjsoc.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gt2apzxeuco.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2fjmocnpv.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gt2ibccvqjb.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjrfltmk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gt2jurykntd.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2ztcmfgzg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gt2ytvgrhbg.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdvlotjw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2txfceqjh.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gt2rmoqjfym.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gt2gvccqwls.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2pjyohhvz.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2urrtrikl.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gt2ibpahaxs.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gt2ipjfilid.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gt2bmmcpwej.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdkxnijn.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpletcft.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gt2barijkkj.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gt2fvzcqufp.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gt2mfrcbdhp.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gt2ncraiyuz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2sjbhuyeh.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2tmicpdjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gt2wmzllidq.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gt2edynjejj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2rydovaow.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjbpphey.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2thgohnyg.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2xxsqdwtp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtyilxeb.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gt2cscbdwhk.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfiyqvxq.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gt2eqvbzhos.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2ssakkeic.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gt2kuelecgx.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2iybpgqpp.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gt2cibgacuu.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gt2zkmcfvva.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gt2iusxoesk.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2opabrvns.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gt2evqysbhz.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2oicvrxkt.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfgckxtq.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gt2vrjhszqh.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gt2inqiqyzm.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gt2sqofwkvf.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2njqrvrcc.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gt2kxlctgxc.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2cbfinjue.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gt2leuadomq.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2idlterwo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ypmadcdo.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kunytakr.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdsvgaxa.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gt2zmqxbboe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gt2niwhylfe.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2dwtnvvzn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2mwdtvagj.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsjoyrqy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gt2tdvrzyck.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2ovjmxojs.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2nafgqckh.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gt2ovpebpjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gt2xafwczjd.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gt2gtvdsglq.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndddztsp.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gt2kwcyvjtj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2eluytjmx.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2aycljqod.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2jssxmyji.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gt2kekcuidj.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gt2yhixuuov.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gt2igdozcbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gt2cuhjzjst.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2qgssyztq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gt2udgrfxqc.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2rbwnkzyx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gt2ghxlpasn.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2nwlwnkdk.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gt2bdrziogy.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2wytxmxyp.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2bbadtljp.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gt2ncvzkoim.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gt2bmdlvlyp.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gt2bbgfbkez.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gt2ckqcfeow.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gt2dwgigpva.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gt2yrfygrct.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gt2wvdbhwoq.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gt2raaaclee.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2qzmhcpci.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2llagffdp.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gt2xemzesvg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxzdtafe.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2rfdbaddw.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gt2rxoregwl.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2atovfibc.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gt2vfgcnbnt.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2jvndnded.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2asvczwgq.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2xsmfyjka.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2moxurzhv.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gt2pgykljky.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqejqpik.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gt2adqzfffb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2vbqkgtke.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2yezcnnid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnubkbqn.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gt2yyectitc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2huwplbrn.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gt2wtchzrko.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gt2ofmievst.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gt2yjfdeode.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2sbhxrogq.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtvekwla.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gt2wjbtlcai.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gt2owtxfvdq.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gt2fqjgrsqv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2pjotljkc.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gt2fwivszqm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ipazjgru.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gt2xcjuziks.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gt2ojmwqwko.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gt2wnsqvdzr.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2fvkpnvhv.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gt2vechxcey.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2utjjzold.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gt2bfokfqqc.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gt2ovmzbxwy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gt2yrgagmrr.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvjpqrky.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2rzfcajfg.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkagpcuv.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnneiyix.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2xpgfjszl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gt2iweiqklv.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gt2whcqevwd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gt2nbuwfxbg.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gt2lnryhhmh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjszmtqr.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gt2gamwbvpq.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2leieuwbt.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2dyiojbsw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gt2fgemxtkz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wiaoedjt.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2goobtdzd.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2caprntzi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2ithojune.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2omvncuoi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gt2hkzewkih.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2icsiqxsr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gt2xspevive.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gt2qosovkrt.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gt2vpprnqyv.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gt2nsmufaoq.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gt2olqncfay.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2zaobeuuu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gt2cxgesgjx.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2plyrmteb.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gt2redbrbuo.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2qysprzcf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2hrtfzibp.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gt2bwkiymsl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2erkktnem.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gt2firehorj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gt2ygllxerk.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gt2ngdmkakt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2pjszbayk.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2cnlauhdl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gt2gusobqao.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2bnkhgiej.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gt2pnhspkcu.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2yjwtbncx.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2evaycxbq.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qspidbiy.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vertxkfc.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gt2mtfpbeyr.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2oiyslhtr.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gt2ipkyvggg.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2axjtjjkw.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uediszrn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrshfqtm.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2dtywkedz.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gt2xfzrviut.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gt2acbjtmef.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2hvwcdepp.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2ahxuonpo.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gt2tsnchhij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gt2pnbixgmx.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2gefhyfqn.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gt2ajuqgoxl.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gt2fodzczuz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gt2fupgknxc.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gt2xiqaqrku.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gt2toofervn.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gt2bsrnjhnt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2ztffqtav.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2aihviura.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2noxkkptm.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gt2vueiqtbk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2ojfjralk.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gt2vxnbxvcd.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gt2hgaatjuq.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gt2hslepebq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csxqxqto.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gt2lxivydzx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gt2omqspytl.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2hywqyduw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gt2laptdzbw.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gt2uebziyie.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gt2jxhlavoh.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gt2txlpzznu.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gt2zxqkxsrh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gatyybpy.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gt2zpobfrak.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2saorkazq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdugmweb.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2srnixoit.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gt2ngszjemm.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2mjrsfskw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmiybotg.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2roakrgeu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gt2gqnlhlzb.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2otlpcqjl.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gt2qeyrqxgi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gt2akkvaojq.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abblbsub.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2livowjjf.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2imiexnuy.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gt2qjkkfvcp.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gt2xewgrvmp.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2miwaomom.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gt2izeystjl.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gt2xevvmrho.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gt2hrvvdopv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gt2smcycrds.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2daesebfa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ypsrkwrh.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gt2kxqapvnw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwybwnlb.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyokdejh.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2hdlhfcxx.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gt2ldjaqedj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2mgyxbmab.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2hnwicxvr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gt2wpqqrlej.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2uxmsgurf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gt2jvjbsbtm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2tugfqrbz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2tiqxeyqj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ksztcbea.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gt2cdnoumwx.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2tuiuemuh.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gt2hmttqyqx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gt2tgwvjlks.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikausybc.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2imxmmjly.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gt2dzgaydsl.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gt2ehimlzuj.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2ctjqbirj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivzqwvtv.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2ivqdiulo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2sjzsvuko.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2nunrmlzh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2hcctanjk.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2veicnayu.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2lkqdofaj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gt2vdnaiqyk.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gt2kwzexnez.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gt2tmmojxxi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gt2zchsogcc.html


<!-- 参考信息 -->