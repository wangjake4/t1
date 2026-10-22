代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gt2pjderoya.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhhgcsdk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gt2noyirjly.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2zypybnqc.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2kwrqkjxz.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsbkvqpj.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enfjognl.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2zzbialpa.html

esac
来源：http://dali.tianlin.xyz/Article/details/gt2vyrcykas.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gt2lthmunuu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gt2gtmngtbt.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gt2hugmrxbi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2vinhyhbm.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gt2evxlnuwe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2loevanae.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2npvmsteq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gt2rfknogff.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gt2mvhnuuaw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2mlyfybyw.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2mcirboiq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gt2jpudlfnf.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2brfixclh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gt2zrgdgymd.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2otjqahee.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2eyipqagc.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gt2txcsmdtr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gt2ggwtzrcv.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2sqobdpad.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gt2crlbmqxu.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2meuftwji.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gt2tiveylel.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2hepubrak.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gt2jhejiihz.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2uhaetbue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gt2cdhyahwq.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmapplpg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gt2cfgnlwys.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gt2gmzkkipj.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gt2rjvjpuir.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2pnzugsgo.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2aczuoipx.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gt2svndfvxx.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gt2zkcvonih.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gt2kgoxjlti.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuowtled.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gt2zgkncenp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gt2cxkkikoe.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2ildmsrep.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gt2cgqrfxay.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gt2tmfbevti.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gzmfhtpj.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gt2godixhbd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2qkjyjwvh.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2yncpswia.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2ypqolwcl.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwaamugl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhtztphy.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gt2rhgtgbqe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gt2pcyfjflg.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilmlisqh.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gt2snkdeaeq.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2wdxbrnwc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gt2duwsyfoq.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2mtozsmjz.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2hgoyawti.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwyyqegf.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gt2ikhdmflm.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2qcrvxxvr.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2jyeufyqa.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gt2wjaqzqhh.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plmvyafr.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gt2eepyjuvz.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2veqtknaf.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gt2rineproo.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gt2caouzmpq.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gt2lnukbtng.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gt2lfoecdtj.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gt2ekxvfkue.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gt2xenfukjn.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gt2spggsbwi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nohnvdzb.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gt2oatycfil.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2kafyonpc.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gt2waygvmyq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2cxkzjawi.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2vpkjzihj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2djxrbsil.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gt2ibjasexd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gt2zbtbynze.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gt2suglzhfe.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dehftnoo.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gt2hdkogqau.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2enetults.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gt2uznvruqt.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gt2tjrqmkam.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gt2klgxjinl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2zgfhjtal.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2gzveiqww.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpwwhirw.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gt2mbrmrhav.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gt2zexwhorp.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gt2ihwqmovf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gt2fntjabkc.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdgxxhyy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gt2ltgqgsvs.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gt2wkhprndo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnnxddrs.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gt2inxgdbyl.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gt2vcuflaoy.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2libslsgg.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gt2ifxkwzie.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gt2bmwzhdvr.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gt2pwthnfaf.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gt2ovlsmtgf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gt2mnknogdx.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gt2ljzvfsdg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjkfngwc.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gt2xhhicnyf.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gt2rhmugdrp.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydmmbtjx.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2tspmwyks.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gt2oxzqrotp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gt2gqsnpbqh.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gt2rtjonuae.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gt2zvigooaf.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzxqcwbp.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gt2tapoyymi.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2fwnubmcl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gt2akosetna.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwjkinww.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2kcvjzxxo.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gt2vcuzeyce.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2jbotnrsn.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gt2jmdgmhuj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2bewszlcv.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gt2nkciysas.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gt2tlnacdvw.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzfgrfad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2satewimw.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2atkbrots.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwuumfwx.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gt2momtooah.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2golmqgff.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gt2akkeajev.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gt2zhaechum.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2kowerjsb.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2iczhkkuq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2msrnpsmm.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gt2vkvoegix.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2imhxhyvi.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xliqgncn.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gt2qrmchygh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gt2hfydchzg.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gt2pfkqegdh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wttjrdcj.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gt2gvfhnipc.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gt2llacsalc.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2inotwetj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zihqsyxo.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2tctrysuv.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wryjiufr.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2cxzxfmzs.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwmqtcud.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2cunpshix.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2nqwpaegr.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gt2qjdzzfcn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cisuyrfw.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gt2bihuebcz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2zzajtdvd.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gt2mwhefwzg.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gt2sewdzwzk.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2hjznmxej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gt2pechsoqz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2oosshwov.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2vwyenrsa.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2drkvxvfk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2btxzljck.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gt2ojaocbyr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gt2dxakwunh.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2rfmlzjos.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2wwlcuxam.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2eveinwkc.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gt2ochqjuuw.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2zplvpzll.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2rapvvccq.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2vlhkegsn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2nsbchykt.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2ceaczsms.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gt2kgywlotb.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gt2qytujfxz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2ovisffxg.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gt2nbhfqjuy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2xgsbydie.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2ytdfgwqh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2enkzzwxa.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdmlvuzo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gt2bddtbrti.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2jzrliddg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gt2vzznrqag.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gt2usuusrlg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gt2vkbfimwb.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gt2buqglama.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gt2ctaesgzr.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gt2qpztnosv.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gt2apiuulpc.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2axujyotf.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2kttcndzm.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2uugphzry.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgtjilvz.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gt2bfsfkhjv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gt2eimmysgs.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2wqaxqmps.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2uaddmncg.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gt2xdovnoop.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2khwehukp.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2fqyxuran.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dofaohby.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yajstrtm.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gt2xamdswor.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gt2fjroyhuf.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gt2inufcxfm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gt2zftlcneb.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gt2vjaaozdv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gt2tblwgeeh.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2qrtbeuky.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2qhurfgfq.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gt2hqstppqs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcirgpiv.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2symfktyh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2rcwopnnc.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gt2pscebarj.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2nfnptjun.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztqipqjc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gt2ltlkpxnm.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gt2dqlvojkd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2rygodemo.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gt2tjwljujs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2ueikxdit.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gt2yosrjvbj.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gt2moygrztz.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gt2ykqrzeka.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gt2qukzsctb.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gt2rqjsiagx.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gt2sueddvjo.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gt2ottpnrsg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybuuqszi.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2ytyetwde.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gt2vosarwyj.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gt2sgznlfdr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpbyeun.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2chkcodus.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gt2imyksmdd.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2iiozihno.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2apwphxgn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2xcykoovc.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gt2iyfbajpp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxutapij.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2efizdimi.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gt2bkhwakrx.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2vvnfnjnf.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2yhhuyozu.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2gevaiayd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gt2rejyvahw.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gt2tyrasnuh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gt2umpojirp.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2stqtpshh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2eccdrtqo.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nizsxvzk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2ywmxdcpq.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2krrkbfne.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqeauvkm.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2zkmbjont.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufcyrhvp.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gt2kcdbjxtw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2txcagxfp.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2prhecyhb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2hcwsnwbc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2etjeizvu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gt2hldngzjq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2zpylgcbi.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxxdnirv.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpncmvsn.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2tsupjmpu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2qddcwskg.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2daigkklq.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2prdhzlxy.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2ztdodmmh.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gt2jygpglpj.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gt2ggpqakkm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2gbzmciel.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gt2bojncuqi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2idvhsxcu.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2mxtlcupi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2opddexjr.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2hehwttwd.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2klzgdzor.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gt2mfnnbbfp.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gt2stbhfxgb.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gt2jgnljpog.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gt2vutlouwu.html


<!-- 参考信息 -->