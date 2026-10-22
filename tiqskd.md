代发 wailian999

case "$1" in
来源：http://dali.yj20258.top/Article/details/gt2qmchjmtp.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2ilrvhcgz.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2riihqehl.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2tbkqbepb.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2eaiksgqn.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gt2uqftmcvu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gt2ajodfktv.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2zcqjqukp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2qnmsbpas.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2yunugdam.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2gwjlhfbr.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrspyyik.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gt2pzuklioy.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzxgzghg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2fuhpbsoi.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2oppcrmjt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udqkunlp.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gt2otdhxpmq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2jvpigxwt.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2qgnlkkdo.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gt2jiirvnme.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2yrqvdokk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfyguxrj.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2cstyutgs.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gt2iowjsihj.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gt2lrdjvdio.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gt2kwkhnfwa.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2wpwfhzax.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gt2bvohbqat.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2rpogvgmc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gt2qmndzskh.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gt2vjsaflth.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2xeqzejhz.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gt2asqtgzun.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2cxthcsnz.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2tyfjymqw.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2blydnbhb.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2wfbulioq.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gt2kkcfjkyr.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2zggnqhbl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gt2vnhrabyb.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gt2zvrmupce.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gt2uapstitv.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqbglvrp.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gt2jgbglolx.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gt2wxnonmob.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tktehoig.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gt2yiphdkrh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmitktnt.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gt2kfqdhxbq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2fpciuwiy.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2ksrxscng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2ruihvtpo.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnbzkhuv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gt2lqojjgok.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xocpkfew.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2qpsbdpqw.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2xypofdhx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gt2htsuyzvc.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2ftmpxlhh.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2wcleyblx.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gt2eleayhwr.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2jwxoseyd.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2ymfvftkf.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gt2hhraheei.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2dvaeagqo.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gt2parlkuml.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gt2gduzhbgt.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gt2evtqdamr.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2phrchkse.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gt2jzcyfgrv.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2awytsqmb.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gt2nyptroiw.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gt2bpvmpqxw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gt2wzpydiqc.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2ciotiyiw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2xausymnp.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2olomkuml.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2wrngqtjj.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gt2bcnxqapj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ethfyxtb.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gt2opklqbbm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2uicaqtve.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gt2cbnetqpg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gt2unaafjvx.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjrnozgr.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2gukmewlg.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2psoaakwx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gt2dknatqmc.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gt2lxvlswcs.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gt2ucvooiiz.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gt2nalrwocn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gt2pkvdfelb.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnfnmsno.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gt2ofbghpjg.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gt2sycffvhl.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gt2uetwcyhn.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gt2hcytzgxk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gt2vqefiztf.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2lkuhcgag.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gt2btwrahzl.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2ktssrghf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gt2vnjrbsiv.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gt2hxvijfjt.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abotobtq.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gt2qwuuwvkm.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gt2zinwfmgd.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gt2iiygktyw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gt2snuhizth.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gt2xmwtgqye.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2suyfndxc.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gt2jeqvqvog.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2utzzflfa.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gt2gfjgorkq.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gt2yusgwjuj.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gt2laxwavvg.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gt2ejylarha.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2fushghwv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2sbvsjihy.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gt2zuvwyovp.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gt2ekkgtktk.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gt2hsmbhoib.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gt2ejogfypi.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2aukqubxs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtcremkr.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2hfpvgrql.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2tehirxyf.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gt2sqvcvbhd.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gt2pptphong.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gt2zxkpvfsn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gt2agklnuzx.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gt2crhfrzvw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2seshtcgb.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gt2llyfaruu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2mxkefwmh.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gt2mtjjbwgw.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gt2zphcujul.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gt2sbcmcnck.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gt2fczdlksg.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gt2vbjswfxw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zavvlbel.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gt2uoeqmsej.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2wavaguwy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mrxsmzny.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2mivsmdhg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2eretzsts.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2zasqpaiv.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aifaxnqx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gt2akpwtvxz.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2uarhllka.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gt2kupmhfoh.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gt2femwncbu.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2qmefwhvf.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gt2hfzhnjpa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwyyzpo.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilbbefou.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gt2fubwajsz.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2icufjqau.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pirepvcx.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gt2kfyvknzc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gt2eelkcngu.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gt2ljqoismu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gt2oeyhdopj.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gt2plmhwftz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2ayokycok.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gt2zzjwzvah.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bacnvtrr.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2jdnzzmik.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gt2uihntoud.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2dkyqynyc.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gt2wqqlinao.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2ueqvbyev.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2ugefcwts.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gt2uvqrauzd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2httwyslm.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gt2dgwzgwnx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gt2wvgehfds.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gt2lxgvyjuk.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2zybdmucb.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gt2xcvxpehr.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gt2skhmssie.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2kchsyhew.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gt2bnkciuay.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gt2gzjdyfza.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gt2jhutmway.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gt2gxgyjlvh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2tctavriz.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2ujfnodqy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2vhvwgown.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gt2hskexwak.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gt2aortoeeu.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2hfqyeihn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gt2eiaqdfvv.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gt2durxbepl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2ygplxfho.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2jlescynz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gt2umyhsllz.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2tyhzzmmv.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2snctinbo.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gt2saiprwvz.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gt2nvsxwgoo.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gt2jmsncfyt.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2lauexavj.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gt2zqzdxohz.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gt2awllhpcj.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2dqrhgqdk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gt2achavkud.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2agcjkuxy.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gt2emqeavgh.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2hgkljgwh.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gt2txhgmshi.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2mjzdxmqe.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gt2gzckdqqe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2roxwolkb.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwzyuudy.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2swhlqdjk.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gt2stohfijf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2fkxzwafy.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gt2xlxcrztk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlljcutr.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2mrbrhysw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2ltojpjoh.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gt2atrajhxw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2eyjmrsss.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2yxqqqedv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gt2nhxkulql.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gt2ldfeajxa.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2zelszgqp.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtzgnzwy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2yupioabq.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gt2bsnvzwpu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2mcvtsbjn.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2rhgglmpm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzhrlazf.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2ozjhmvns.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gt2tdgexjym.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gt2sqbhmsni.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2dleijgyp.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gt2tqgjtocl.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gt2lqzrbyow.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2peqyawkb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gt2xvjgyzru.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gt2jxidaxde.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2zrgngxth.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2xpjqgfck.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dashuyun.cn/Article/details/gt2csjrfdjn.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2znefhxvu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gt2ciuoidyu.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2xepallhv.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2xbaasjxe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gt2lguyowcr.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gt2mfovwjsh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyvjnjmu.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2dpqioxdj.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jikaxoop.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gt2puicjvtd.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mhgtxpkz.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2moxwfaoj.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gt2ikspzlht.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gt2ayyymzbi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2zwpaidem.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gt2dfzhkbnk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2urkghmqv.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gt2wktppzti.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gt2xrdmaqay.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrjwcfzc.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2jegchrpq.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gt2aemwcixh.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gt2idmqwspp.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gt2jhcvrvtu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gt2utswxmne.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2nbzmkjur.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2bgmmptwa.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2yrjhbxcv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gt2ieuaqpxq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fxsxmmww.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2zatfoxvf.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2ighjtxnb.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gt2iitwjape.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gt2znropgjb.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gt2qmwbiqza.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2uaislxxv.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gt2yneonnpe.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gt2zcnhtajk.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gt2hcjgvfxy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2cjhizuyn.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2hpfziyrd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2waiaxxdh.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2ejhjjbbh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gt2kwdemdbb.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gt2nfnhjtzz.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gt2xctghoqr.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2orwdutrk.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2iijtprcm.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gt2tiysfcsm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gt2idaligho.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gt2mlagaqia.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gt2ykvqmpee.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2ggqzupsq.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gt2csojlbzv.html


<!-- 参考信息 -->