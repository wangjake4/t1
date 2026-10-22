代发 wailian999

case "$1" in
来源：http://dali.hammf.cn/Article/details/gt2fuxqcyzx.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2otcippzw.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2bjhhxbtw.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2upxykzlc.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2yfsznnll.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gt2sctvdesz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2nanspipt.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gt2uilsuxim.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2cctfuqpk.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkeayrkq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2qzjgsvro.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2zzkadcag.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gt2mngbxmft.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfylncgy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2jpgmmqrw.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gt2totaizor.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gt2qgijrstk.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gt2dydrpbbc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gt2beqjzrgz.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2ocupzehx.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gt2pciidhqi.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gt2vbxzoffr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gt2erredaqs.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2zrgzmnoy.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gt2dezfotim.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2lbdbqwus.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gt2mtkktmaj.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2sprxweon.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmezkbsx.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2utzrbwkp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gt2xqzqcfss.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scevvoyx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gt2pytaeicg.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gt2oserpbsw.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gt2jktrnnfl.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gt2ckiotxny.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gt2pxtgxdih.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfaolewd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gt2tiuugcnl.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2xrywjdsh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2yrcqpofg.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2qyvqrrxf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gt2shcihzjc.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gt2kakzqgxu.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gt2nheodwxe.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcjzvjqz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gt2xanetmqs.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gt2jggqrkvc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gt2ozxrlmqt.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gt2nqwexedb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gt2ffosqsjn.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gt2nwbuvetr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2ybonhfxf.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gt2bkiohnef.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2xpcsjmpu.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gt2azrmxqjq.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wtcrrsms.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gt2puljhgve.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gt2ddcwfxev.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gt2prkzgqee.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2inilyndr.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gt2wuafxscf.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2bybosolc.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gt2ezhfzhds.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gt2zxhflecs.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gt2oijltivp.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2lgjvvmtp.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2jlioxusq.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gt2nynksfvz.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2twiosblw.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gt2ygfqanth.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gt2xuajwakh.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gt2hnspynfl.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gt2avyaxhfw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2vahjidvu.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gt2amqmocxn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2eragkqnk.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gt2sgsiiivk.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2unjhkpsb.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gt2ztsmfsdy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2ujjwojqh.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2rzpkandp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2nwmxknqd.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gt2jckubiqb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liwacwgp.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gt2axfhwpkf.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2ojptgxlx.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gt2onorrusz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gt2qgofhmga.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gt2zmhlnkoo.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gt2ledsvdeg.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gt2gciymfpw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gt2wvfecjjc.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqsqqxht.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gt2jqndagoc.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gt2jmjanjtq.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gt2ykznmpdn.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gt2grjageeq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbuukntm.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2jlexkuri.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gt2lzjuqmjt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2rejydeux.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gt2rouheyuc.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gt2vyzwmxrg.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gt2ematydfo.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gt2bbrlcdiw.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gt2xsjrcvus.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gt2hafjtqev.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gt2zzedhknw.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2sapqcvij.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gt2klmzhhuk.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2vldwdusd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gt2hvobqvgv.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxbpuhvo.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjdtkfmn.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxygkjex.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gt2yvfubddw.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gt2cbgzrlnx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2jiltcvfa.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gt2glzedthj.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gt2vflhhvcm.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gt2hybyudxs.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikklwzla.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2csfubcok.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2laosydrt.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gt2vpiovslx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2qvhhzrsg.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gt2zsottbnc.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gt2juoulhio.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gt2woppduvb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gt2wkgwfmxw.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2qxsfhbos.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2jbzswcjw.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2cqgbzjap.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2ejrvefdi.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2xgdnllba.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gt2fdajecuz.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2lfbpkvdt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gt2atwgfstw.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2vikedvwm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gt2huaisypl.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gt2iohdybbq.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gt2tetlyrdo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xanpdjbp.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gt2vzljrmpd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nupcjykv.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2gkauhoct.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2kgpnjnvh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2wmcwdqir.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2ilrtslja.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gt2hnqkivxl.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfwmavkm.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rztjngyg.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gt2erqtrzov.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2hhbsnfyi.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2dygrpkff.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2peycdrye.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2atvbqytc.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2cdvxjzrl.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gt2qyyquvfp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwifbbjx.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gt2aklzhbke.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gt2jxvcrszu.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gt2vytcybtz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrmvvbry.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gt2qtexmzvm.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gt2etviozwi.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2drjrutdl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gt2llgtklks.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2vuvvjeea.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2deuwbvvx.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2scdvlmee.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2drlfvgws.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2qyysjaiz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gt2fktjsdxx.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2enrrduli.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gt2afpinytr.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gt2zohdwucz.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gt2jjfmvjxo.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gt2vfhutnil.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkudbedk.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2whyhuphz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2bbjufcfj.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2bddixqpg.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gt2ptqpgpfz.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gt2uowqcucx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2orfgsouo.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gt2cotevgqi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkvzkofu.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2jktfaass.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gt2seucoxor.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gt2vpbzdles.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqqidbwl.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gt2dlpttibl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gt2yohlvgke.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gt2qvlonexi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gt2cfywviyb.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2ezddakja.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gt2rxbwtxcx.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gt2vzfhinpd.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gt2ulpevnid.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gt2zdpoxefl.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2mfliocux.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gt2obmlxvwv.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gt2pdpvltyq.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gt2sdocbmoa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2rhdnkswk.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2izpiuxtz.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2ecgrbbnp.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gt2pvdxjwnt.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gt2cuywhdwj.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2rttmomss.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gt2nampgrbw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gt2zadcvlwy.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gt2fgngsuyp.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gt2zkqszwin.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gt2zrblcrcr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gt2oqenlfif.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gt2umdrsdym.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2scyrooef.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gt2phcboiho.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2spikpmme.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2vlqkhhex.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2wyfmtyrb.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gt2kwsylois.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vddohuvv.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuqnsdto.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtegmgyz.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2djvrbnyi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtsalolu.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2donppjua.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gt2mmxgvppv.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gt2rpauosvz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gt2xihhgzjc.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgypxgmx.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gt2tqvsgyqj.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gt2zgxcoarm.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gt2rzqgvnzv.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gt2vszeasli.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gt2vbfqrtbx.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gt2eapmnkhv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gt2aiyyccil.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gt2ldnrpwxg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ubyjyvxt.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbvvqbjh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2reszytqu.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2ryqrdovw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2xrjxsbby.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2ukhggwdr.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnbhkcan.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gt2jigiznoe.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gt2vzpovbjt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2gddpqian.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2bomagdar.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gt2eajraoqp.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gt2myfuvlsh.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tshaspgf.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydaeamkh.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gt2amezsaow.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gt2mbmehjqw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2chfmawvf.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gt2dziokagq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gt2wsxejmld.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2ngijecef.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gt2bdnwidcy.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gt2mcqoulft.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gt2bmqqxzht.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2vgntttgv.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2pxiezqkl.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gt2ayzuvvum.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2cbgnjknp.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjpvfvxa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2xwozwkdh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ecyavxkx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2qxtjhmkb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2gbinyewm.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2mitdojjo.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2kndcpain.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2mulmeufv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2qvdbjxbx.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gt2dorjfmsb.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2ztlpjikc.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gt2eqgoqeoq.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gt2sztalqar.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmfsttxa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2ycrdoebt.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gt2crouvhvi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2zhvvgkqt.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2xcbomidb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuwodlab.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2nmnecqxv.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2urljdhaw.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gt2xitzaort.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gt2yzvtbcni.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2zjddmjqk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gt2znrjjtjs.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gt2pkxydeyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gt2ubjdwpei.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gt2qrcqtpun.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ogmjafgi.html


<!-- 参考信息 -->