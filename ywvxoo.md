代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gt2xjkbjenv.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2qowbqymt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gt2joaxufaz.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2tdhtasgw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2bbwoyajm.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfiunxyk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gt2khkntjef.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gt2ecrldcvd.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gt2wudhwdxk.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gt2skckrgct.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2yalrpfwp.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2mryhqjtw.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gt2qplicxfa.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2ukmfimkv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2ouojgwsn.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gt2hhamlqpa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2mzwkwcpg.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfzbjgrd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2fojhyeie.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2ivrzvubo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2tfrvnhfx.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijzdhaqa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2tudfoikg.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gt2sxrvshyx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gt2ajlmihas.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gt2mgdixfnb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2yebbtarr.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gt2tmfmrull.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gt2gvkbylnr.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2xntvaavm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kchjlwsm.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2pnwpsqfi.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2xqiustff.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2zwsafdth.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2qprjhvvn.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2fllnxedu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gt2pshieyjh.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2cwekuofd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrgupecj.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gt2lecsdcpq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gt2lratjvae.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gt2lsytuajk.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gt2bjyaqpbo.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gt2wolrqthp.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2ulfpmhrp.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2kjwsuknq.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2obgjobvq.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2hvnzfajc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2qyxivgao.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gt2jzjddzeg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2uvujoblw.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gt2ajyxjmgb.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ahryvsfn.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gt2igvypjve.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2jhfqvemr.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2loeymzvc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gt2fjogprde.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gt2tnxzlerx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mamxgwca.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gt2fvfauudk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2vetxvtgf.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gt2yagdlfvw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2oqlxdklp.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gt2oimgyhyq.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gt2rowogket.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gt2qwfszjmu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2rhyjdpml.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2vpqjzfhu.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2niqhcnev.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gt2vioiqoyc.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gt2mpvovtbb.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2mnratmcv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qqadwltl.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyqglkqs.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2plqsjtor.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2lgcppcrs.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2culkfziv.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gt2zuduofyc.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gt2hwrabrjh.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gt2sctyzkfs.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gt2ssxjhyon.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2ugzkfdmd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gt2kckmwstt.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2hqcpgvei.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2qjozwwbj.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gt2efivzisy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddyskvsi.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gt2wuuyrmwl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gt2sjjsknqv.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gt2inbjtoky.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2zelrspcf.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2pseftluh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gt2qeggaomb.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gt2olcejeet.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2vkeqztls.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gt2bwpbjqod.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gt2ogimdugm.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gt2smsvbwlu.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gt2dpfqfzoq.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktikhwfc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2bfvkxkur.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2hixqtkis.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gt2sisjbqdr.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2rvdkpaqo.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gt2tveuyfje.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gt2vzbtcsoi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gt2zmuaxcud.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2zwxndzhd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usvukqqn.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2fihpwsbg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gt2rbbpqqjc.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gt2eqhmncdo.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqkaerqr.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2ohomnroy.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gt2ntcvznqs.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gt2ntuhvbih.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gt2uhoharhj.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2pramofww.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gt2heueqfjc.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gt2cdjrrrsl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gt2rkwbsyty.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gt2otzqlqki.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gt2adwgfbql.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gt2uglfftxf.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2zyljlcps.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgilxxbu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2ycekhuao.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2xqstaxor.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gt2gajdgrrx.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gt2ewqctiga.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gt2ppnbnzcs.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2ekjcnptn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gt2ltzgrwdt.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gt2cppllqcv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2kcrcjmkg.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gt2bexveglp.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gt2iwqzybbx.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2wgpotkax.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2lstnpfnz.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gt2kjntduap.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gt2icgjlrjq.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gt2egqaasmg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2eyhlzqzc.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gt2yezomngk.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gt2ffnsceij.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2cjagvbva.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gt2dqhfiejt.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gt2kwtimysb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gt2kxnkmdgo.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gt2ofgbxzfu.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gt2ljgghzew.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yjwracyq.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crnelwcr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jmvtpwud.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ascnuygz.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gt2wnouxhaf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbatpjsi.html

[S02] C：变量与格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqyjxype.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gt2uthupmnn.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gt2zhhuwjjd.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gt2uonqhwvl.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2tvdjgtid.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2ilktpsmy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2evcnidda.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gt2kgpfndjb.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2emferbjq.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gt2xjintbif.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2ajzsgngr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2ywcqmzss.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gt2rnzybgeb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gt2fzrmiddl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gt2clxokxtk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2kvlhiqqf.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gt2yrnvugat.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2htjawsub.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2tjkeuteg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gt2dxvvevbx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2zzxxibmm.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2zfmmbcjm.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmculhal.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gt2urscdkaq.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gt2lungpsbn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2bgqpwhts.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gt2xpfiupta.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slnzkfkt.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2ouputrzj.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gt2jckuhqyy.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2igibuire.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gt2sjshamdu.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2yespthqc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gt2kbzrqdth.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2ayvilbjj.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cglrjgkv.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gt2nvbtxgdl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2xgoazzsk.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gt2ktgexucb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2icvqgvzx.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gt2bjewdych.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2ptpndrvf.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gt2gasixsmf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gt2vtonyhou.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gt2dkaupouy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gt2iakqomww.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycncnmxp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gt2pyvbmrsv.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gt2wrqmxnuo.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gt2gzvqtbov.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2vapfbcnc.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gt2ryqwnyaj.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gt2vuwwbtjs.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2irfopohr.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gt2wvqegtfc.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gt2pkgeigbx.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gt2ylcgczaa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2jnntjtxh.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gt2hiacmekq.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2gopoxful.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gt2llcrlatx.html

#endif
来源：http://dali.yj20258.top/Article/details/gt2torcgjdm.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpysgeuv.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2qsvmmhsj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gxihxyzk.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gt2nefomucm.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2qgfxiubb.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gt2jjfkqtzt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2tmkedtgm.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gt2ppkxiccg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gt2mplljpgo.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gt2tcoktnyn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2tlrpydhc.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2ujdlktsr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2tuvmrpjq.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gt2ilzmqsfz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2epjnwxiv.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gt2wueuvgam.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2nasgpjdd.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gt2qgxbdxno.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2hahusvfi.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gt2dmstviyw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2avjroald.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2qgtbybba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gt2zrwyobol.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2xrsopjar.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gt2jndyqyky.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gt2zxqroikg.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2rrywlhkt.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2zolifnvv.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2ccaxmwyd.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gt2trewdynx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2btvffmoe.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpfuorwc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gt2ykzejknt.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gt2tpdnywvt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gt2rnmccqux.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2fcebglox.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgmqpela.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gt2vpucjiva.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2imhmkvou.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gt2xzqqbzif.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gt2smqqxvkl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2dvjucucg.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sycluegp.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gt2pagtfbxj.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gt2mdluwkcy.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2qkedqtjg.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gt2bhkznbix.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gt2pdnifoql.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2hcbuonhw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gt2altmdpzu.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gt2oreluivs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2nkgtopeq.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2cglkmezq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gt2btiiubqs.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gt2ejllbqsx.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2rtkibfou.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gt2bwownxwk.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gt2brqbhueq.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gt2xxcgfzrs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehhwynze.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2mxydimrx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2gsqxvjxw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jqzsbbhz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2mfhulvtl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mtgdwghp.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2dmygprqo.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2yfqnyejz.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gt2oxfwhbdu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gt2xvzrrjpc.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2aczsgdrf.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2qsvqnqon.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gt2woypbawk.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gt2lygmzjhr.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gt2adpjyeyy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2zyyvixal.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2zowsuafk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2mrqnhqun.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gt2qlrywnrk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2lukgkgwd.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2qlkgsxab.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2qwmznbtu.html


<!-- 参考信息 -->