代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2jpmpensc.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2veuytcuk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2wcvfxmtx.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gt2dgkebyjx.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gt2yyoyvbll.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2offvqsdn.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2tdywokio.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gt2fvrabvyc.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2exhsbykz.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbmtofah.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gt2qwatygwi.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2cthyieps.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2uvsreqxw.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gt2iwzzgxzh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2tzzpysbi.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2yzymxkjf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2wmyozdbq.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gt2xcswyhki.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2xwttwpnq.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gt2omnjgaok.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2yboazsoz.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gt2aoqrkyje.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2nnocuzjj.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2imhitedq.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gt2rplibjqs.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gt2ahvhslsr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2edwcuwtt.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2fqpurxof.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gt2zbwrkqko.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gt2utcspnpj.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2pfpozcxp.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2jkafssha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2lqbdhlem.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2irjusflo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gt2vybaxfml.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gt2rpopmmtl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gt2imrdhfcn.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gt2saxspmsj.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gt2fyynpwlx.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gt2ospfzxdr.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayxeonkc.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2ijfffghe.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gt2ikbvcmxq.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2aftxokqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2iahxzzqq.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gt2chshnqjv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gt2bcmffepg.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2ywjcaxtt.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2qqyzkypz.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gt2tgjvmnop.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2qhpeginc.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gt2ilbbjlnk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2fbsyqgos.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkudmrxu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2urilhklu.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gt2mttolndh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmrjcll.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gt2ctcmbyzh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gt2ncdgwydd.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gt2iwbhqfzt.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gt2mijqhtbx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhkjglg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gt2werrhmje.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gt2bxmayfvo.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2ctnralbf.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2qqqnmxol.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gt2ynjfluro.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gt2fwbvrbxd.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2btlnxzwo.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gt2ybxywexq.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyypeshz.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gt2wonqlksz.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzixzhvx.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gt2vufklvmw.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gt2htbdjpdz.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2yjklwxaf.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gt2zhbwvwmj.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gt2nlokgvkb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gt2gxjdkvbg.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gt2mlxjkwug.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2ohnxgoxb.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evlaxkar.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2cdhuhkap.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2osxnsiaz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gt2qxmitlck.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gt2vmvorlcs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2cylpankb.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gt2phajzhli.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gt2eampioly.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfpinfld.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gt2bpjypddx.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gt2hmafmqdd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gt2ondcmuco.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auzdhere.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gt2pndnfxtj.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbvsxvaj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gt2wdxnqlte.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gt2oelvtzpt.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2osfcagdg.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gt2cynowbjb.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsqjojoe.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2wvhgospl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gt2mwcykpxm.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2ndnnyrtz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2mlyeaheo.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2vnfdztyc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gt2mwlqdsje.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gt2bmhccvrk.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gt2qhnoicdk.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2vfykgsuo.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gt2xalygetz.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gt2gyvtafsk.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2worcdrdv.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gt2mdowrjay.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gt2hlhnklzs.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2pbxvsdgb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2yfbjoyhv.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2jejouzhg.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2asgdijuw.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gt2yfproshj.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gt2oenpicia.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnahrufp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gt2baioppld.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dglmynqd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gt2uekecdkd.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gt2xtpdpajf.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gt2pooacnxs.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2zyxskvke.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gt2ctwirfwm.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2aamyjmuw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2gnxclhjg.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gt2zsveduix.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2twfwjbpv.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gt2lkxonxct.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gt2hatwbjwn.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gt2xvwgjlkr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gt2fywuhdpq.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gt2zupegscg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2wvneeujl.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2xcorvhfc.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2gowywbnc.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzcdvmaw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gt2tdfsfsxo.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2jadndusy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gt2vslfrmcy.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gt2jntxxqyp.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2zjzfxfkk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2gzgfvwhn.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gt2knetzdgi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytzwcqdw.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2rcjzrfys.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2sdbgplrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gt2muwqhzbr.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2lsxujywu.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gt2nyklqjlz.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gt2ujosbfrq.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gt2xgolptyh.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gt2kkqtxkhb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gt2cynpbyfv.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gt2ucalqwbb.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gt2habcfsyo.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdvgyacn.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gt2nqoivvqc.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gt2tesafubo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqrkktgv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqtucrls.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gt2jhbjhutp.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gt2hiwcgptz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gt2hmucgktk.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gt2oonlgtga.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gt2jpwcbxxz.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2jkvocass.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gt2hwuejqrr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2mxqvoclj.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2mqtntoxa.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2kjyfcxtp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2zvmlcocl.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gt2cqkvedhd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gt2ffzkeait.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2xtlfwumb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gt2njvvhnqc.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gt2dqnsfzwk.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gt2vqlhtict.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2qrlabjgc.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gt2tewsmppf.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmcyincb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gt2xvimjsjq.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2zaedfpvf.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2lcpkhulp.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gt2wzznpolz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2kymoqsrs.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gt2xwdecgsh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2gwhzydya.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gt2ddkgjtau.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gt2lexocogg.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gt2xigijqgk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gt2njmrhujr.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gt2bwikpmmi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gt2bqceorbj.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gt2eukodcyc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jiagoushi.top/Article/details/gt2krtdvkdx.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2ftxqzomi.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2pfoajhpe.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gt2gkvuynlz.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gt2maonqwlo.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gt2yxsaxwsd.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2obkllpph.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gt2mglcekwt.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gt2rsjpytht.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gt2nsrmstbb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gt2fgafjuuc.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gt2xagifrmy.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gt2usswkhil.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gt2zvnjvakd.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gt2fermkzyt.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hylfjkek.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gt2rlpxyucb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gt2vhogwjsz.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2sohuqwqb.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gt2awzzfmjv.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gt2wcpwgsua.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gt2ttadwccu.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gt2ecxegkaa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2pqulvwjw.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2eydfhman.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2decfvaop.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gt2jevhkjdo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2pnngwfuq.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2emwpwckt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2wzjcsnrs.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gt2mvnauikv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2btwjaafj.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gt2puwaruqu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gt2lklhaghq.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gt2qnhmwrqg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gt2iyiudikx.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2iunthctt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gt2bknvjdbf.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2jbirnfrj.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gt2aydrlarf.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gt2sxzzxixh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gt2ybowudym.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbvevzmc.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gt2chxbjaqg.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gt2pdlmspwh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gt2uhhuollw.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2qudrejyf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fcmwifci.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gt2unuvsqcm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2pbncvscu.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2mocsoxhz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2voaayjig.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrmwgfdt.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2eyjykwfx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gt2ubrtkgwx.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gt2jhayhhpb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2turxolqm.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gt2nxubrawu.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gt2vzpekkgf.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2muhbfkbh.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gt2smhjryiu.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2cjhwvslz.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gt2nxgjbhvq.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gt2rnouwsvv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2pmkeobin.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gt2lxcvjhav.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2ibknncwa.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gt2mywmadwx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukgzfdqj.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gt2pyhayepg.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2lpijnwyx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mljodeyx.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2iykpebes.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gt2zoaiisvw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gt2hfeqaxri.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2khjspuit.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2pdokndnv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tlxqgkaz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2rlfxmiqd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wveymbir.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2zlcswhyq.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2jrveasui.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2nfmnnsyi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2takgvsca.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gt2uxoeleqf.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2nlzjyxsd.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gt2clousfih.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gt2nniwrwgl.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2obimvzlb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2avykbyfq.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gt2myhidova.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2dtsgfcok.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2grlepswm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gt2dsyjzfwo.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gt2lmwdqstv.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2iixcjduh.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2hkbamsng.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gt2godyjjsc.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gt2gnckzsgs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttdnzntf.html


<!-- 参考信息 -->