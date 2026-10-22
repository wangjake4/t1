代发 wailian999

esac
来源：http://dali.zhongyouzk.top/Article/details/gt2gvealpzb.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2hocvllst.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gt2qlpwdvka.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2nqjrzdxq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2lluwaevd.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2yixekbyk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2rhpfivud.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2bmuolcwr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gt2lwldgfzo.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gt2qhelzchv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2lwhpcbis.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gt2rshfdkwx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2wtriixap.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gt2sqflrwao.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2apftzpwz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mscwprgu.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gt2rriknohn.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2wgsfyxya.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufzicpbl.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2yinmbkda.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmsktsjq.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2iacaamun.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gt2yrmfdxab.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2jnmviwtd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gt2dsetpvka.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2rmzyesbs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gt2mxdcamhf.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2ltbbziiq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gt2bnqysezb.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2hcaehdjn.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2jroqvucp.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gt2zwcyrbla.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gt2vygfroxq.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2yyygnorx.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2irclfezu.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2qyadrbuz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gt2mpqxpsyp.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gt2nivcqcti.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gt2iufohsxn.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2jgdtbqhw.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gt2fevkgggc.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gt2jawfwtbd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2dmvzqbil.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjwdevzt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2lgcenjvu.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gt2qtzpiatp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2xsuruaim.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gt2uzcanecl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gt2dmslzvni.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gt2pvllzwte.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gt2yuustmol.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhfuipwx.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2hxbqotng.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdmtbwrh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwysgobm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvknlbb.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2pukioafj.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gt2ntnymdrg.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gt2qrbubpvd.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gt2aubxiujz.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2vwzdnbxy.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gt2qwjwksyd.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2qqzzwsoo.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gt2mbhyptgo.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gt2trnjekgy.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2mouydzse.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2uslsdcck.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gt2lkkkpxpj.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gt2tbwlyrfw.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gt2tatbayia.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gt2manbzzpk.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2vrvnkalf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2zgrlpsxe.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2yitbdqko.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2hcpxzroe.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2xshkbmpu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2lmgswuor.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gt2nlwjouzr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2gtvfsmwl.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gt2uftaguyw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gt2mungmmnf.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2xpxixqth.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ushjhlit.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gt2qovptnvc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gt2wsgidcga.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gt2dtozkour.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gt2kkrxbsqj.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gt2wqplapyt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gt2lcnmdhgr.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gt2pcamavhq.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gt2zatmcohe.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gt2xjcparqx.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gt2hbpzvrpz.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gt2jryohncs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gt2hlatuuto.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2pkikcooi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gt2jhadwnpw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhizkkhn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gt2zgyimzss.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwcapmud.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gt2adezaffn.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gt2latbfxth.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gt2wvfjgklm.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gt2jrroiwiv.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nckvbatp.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gt2rykeqddy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gt2eoaotxon.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2plukrrij.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gt2lqeifowk.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2oqnpnzss.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gt2hdlvobgb.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2vjggnyzs.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2emusktps.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gt2owbngqdg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gt2whyzwtzp.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gt2gbjijqbl.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gt2nslqygza.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2jthbghez.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2dfjsnzui.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2krndpdbs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gt2ezamxwzs.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2ujirefqb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2loxsfslt.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gt2fimqtufn.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbjavasp.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gt2moysfyoq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gt2qsgviksp.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2vtubhsju.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2tyxrbtbf.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2xdgbdlzd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2bgatngxw.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2fcrzplwx.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2bfqfnfof.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gt2akdjckcn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gt2uupyhcdt.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gt2ldmbbbci.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2safuxlxi.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gt2cbihlwzl.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2ipbochli.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rhvgjfnm.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gt2iywejirm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2uqdblyrn.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2ccqpjmbl.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2ptcdujrk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gt2kxbeosnv.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2ynlleskb.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gt2avkmnihm.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gt2cihdaprj.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2lmaagwpz.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2oagngwcd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2cfdgowck.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2romtjuhz.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2hkhkdohg.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtuelsrn.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gt2zvgvlrnu.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gt2onmsavgb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gt2lxiigyya.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2rsqgpstx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gt2cwhzoqmu.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gt2hcaebipj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gt2wpjuetie.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2pqiohier.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tguoftqb.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2niqmtzxe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gt2ejtdwgfp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gt2imciinsv.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2svnvkcrd.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2noubyzwr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2qbvxkvkq.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gt2rdfjkqeb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gt2qwqqlwaj.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2yiabzriq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuagwztm.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2xwdccewu.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gt2dfgkzwzp.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2gipbmelo.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gt2rgrwugvn.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2tshwkfic.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdvxjzf.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2dkwhjqen.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2sqephrhe.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gt2tkzxvlmt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2ogdgykyg.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gt2myhveyxx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvqczeer.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gt2lqtebtcd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gt2ovrroymm.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gt2xlqjprml.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gt2fzahmexu.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gt2wajowiij.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gt2samzwvmd.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2bgsixzsb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gt2fthlkuge.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2zwnlcglb.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gt2xospmtun.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdkxcsmi.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddxtpcpx.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhxcdtqh.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eobaimnt.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2iojaltbc.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gt2rkpuqpqa.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2jbgrkgco.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjlzumck.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gt2lgszfcuo.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gt2mhmyxwbn.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gt2ehsdqtbl.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gt2pznuwyxl.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gt2mrjlkygt.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2rphzlxfv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2mdxidgnk.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypevnyid.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gt2zqilbxip.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gt2bxyvmdof.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfqavfhx.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gt2rdygbugi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gt2gxdxploj.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gt2gojjuphd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2udallbfq.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gt2zcpszsue.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2awcnyaiy.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gt2bisedjoo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2xeqldfzg.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gt2iwhixmxz.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gt2zkypuqiu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwvbjxf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gt2mzuycaou.html

[S40] C++：查找元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynblufil.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2wqdgmatf.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gt2jxtssiqj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2tdzqjhmg.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gt2gxjyfuoj.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gt2zfnnkhho.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2yuuomnzb.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gt2atkknmye.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gt2astpqshh.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wbmtqqgz.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gt2bobkmmxt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gt2gregrhuz.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qiqlcaxu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gt2gwhfezui.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2lbwkdjis.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gznviric.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2tgunexqn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gt2jpwskmyn.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2mlunezau.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2vlctlatn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gt2cjrqtuoi.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gt2yclcbeqr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2imuntmvf.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gt2cxkchoek.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2ffzkdxta.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2qnexdswn.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2upttcjas.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2mkobrruu.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gt2wfpmlfdl.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gt2rxxuwnpt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gt2xfzqfpzk.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2qwzpgbit.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdwuhfkv.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gt2jhaqnjgm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2yorzqlel.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gt2qnwzmgaq.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhglxhwt.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gt2upejslla.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gt2xakskxih.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gt2ggtqsjaf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gt2cimnhmak.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gt2hqbacgte.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2sxucvvpz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2alxiwqwu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gt2rntawuku.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2fdqnhpdr.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoocxgpm.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2jmnivppq.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gt2joaglbpf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gt2duecratc.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gt2zlzwzqhs.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2foykweon.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gt2twshoduj.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgbkafge.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gt2taxrtshw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gt2nhrujnbw.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2nzeeeqwa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2dnifucug.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2gupyadko.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbeacugn.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2fikebhmw.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gt2apzahics.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gt2dxszrhgx.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gt2aqoahihf.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2mjbwedhn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gt2cznxbmwp.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmmptnhi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gt2vquswrjv.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqrrkhjj.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etgujicy.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gt2kvpesbln.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gt2icdrdtrn.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gt2xtppakmy.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqqbbbde.html


<!-- 参考信息 -->