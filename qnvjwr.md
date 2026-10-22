代发 wailian999

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gt2bjrkuqmq.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2auklmnml.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2xvexhrpt.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gt2ymubrbfk.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gt2hwvfzfuy.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gt2skdeaghi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gt2fpyvgdkl.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gt2zmvnfsie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2krekeuxy.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gt2mwwebfls.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2wcnpvhru.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2cnnigahq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gt2nszjaobb.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gt2ftwqmqku.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2xrptmwqh.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2yadekqfa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gt2gocyumor.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gt2ejonvdjf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gt2ejjhkidv.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2kfjsusgq.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2cywgtomw.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gt2wejaujly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gt2vdiejymu.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2uvbrvvxg.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gt2fqjgxlbh.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gt2jajcxutz.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gt2qsdqlkcg.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2irdobiax.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2bhjazbza.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2kdfvtkdh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gt2umvqzevg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gt2jpsnrfta.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2zxoyqzol.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2qbxdaptd.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gt2hrfxcwhs.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gt2cllifazr.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilpwkkqw.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gt2iyacumcw.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gt2zmwgnqil.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2stemfptj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gt2kifvmpxd.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gt2seqarzlj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gt2kmvumfek.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2tsfkfxxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gt2vzalrvem.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gt2cqrwojeg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sjxidrng.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gt2vmdohrmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gt2tuwweypa.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gt2ddwjtjsv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2bdaskgfm.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2xictxyrc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gt2claqfuno.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gt2sgqdkoqk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gt2mcrbooqu.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gt2homdeoqs.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gt2anhfcizu.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gt2lafebnys.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2odmnnbml.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2qrzewtmu.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2acqdrnyz.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gt2cbhdmnyp.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trvpjqee.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gt2vhemdhtt.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2kpwlhdux.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gt2xtzejhfn.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gt2djvvkwet.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqrkxfkt.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2jbezrgrk.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gt2jtfpibmr.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gt2swkjkwcm.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gt2ahybzjtp.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gt2wzzyzywn.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2orzrcpxr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gt2dccblpbg.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2aglnkari.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nseaszws.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gt2lkqjhnmc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzczucyy.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gt2dgecidvz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gt2hwoeiflm.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2mupbbmqz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2adijdkzg.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gt2iwyzcops.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gt2tqxysalg.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gt2pdtipqyw.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gt2dudpogwx.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gt2bicwjdky.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gt2zidjhxil.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhfpltxr.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gt2vztfmnic.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gt2euujubzv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gt2gjuiejgi.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2efmyixuc.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2nmjpplym.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gt2awhufaiw.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2rhzpvgbh.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gt2xxchvpkb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvsidmkb.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2burkxoht.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gt2wvuufvln.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2iohxhkke.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2llihhueb.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2amyjnikw.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2ttfolsdm.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2vbgjrozt.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2aefwlunj.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gt2gfuvmouy.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gt2iqcangno.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2vdptyjte.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gt2yhywndqt.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gt2leiqtrcm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gt2twyqguad.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gt2pmqkofxr.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gt2hcwbexjn.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gt2ttbgejlp.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivdditfn.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gt2ydrpqldw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhyociez.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gt2npepzixh.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2yfofquka.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gt2zdkrmmfz.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2rfpkcrod.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2ngjividm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gt2aocezqld.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2wyhwbtuz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2qcrikwwh.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gt2oxvbduon.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtfhdxuo.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gt2vcjmswpn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2aalvcmor.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaenmjya.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gt2pnfcxhfc.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2yenpnrwv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2xmsffalb.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gt2iabjlokb.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gt2vmxmeyqq.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gt2oqmdhaau.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gt2zzxykzdi.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gt2hhzmrqiu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gt2zyvsdvip.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2zxejodmn.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gt2qutorfdd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qxqoigkk.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gt2odyfcxdy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xtyxskgi.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ghhfdyyy.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gt2apnzvfna.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfvhyobn.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2hqcnajna.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gt2reniqexv.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gt2diggdpst.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gt2ufdwmqyl.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gt2wpcpagla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gt2mfpkjwxg.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2soidkrhr.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2hokzwsag.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2dvpgqabt.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gt2iyycvmfx.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gt2hfvamchf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2xpfhzjvq.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gt2pfkcquuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2irgsyotq.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gt2ioaexzvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2ecrjicve.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gt2fhbxoctd.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2irmqbisy.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2vwfbdnnf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gt2hpqnqjkw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2reerielp.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gt2crbjlbis.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2wijjeoct.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2mrqlafbe.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2udypdkgq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gt2kvuopupw.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2lhgzcxun.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gt2sbjxtpnz.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2ohyhkelx.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2jkrarfgp.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gt2bdlumkht.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gt2ijybdxfx.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2arddfcpk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jovpuxbx.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2rlmtdaaf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzdopzj.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2ltybhydz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2jtbuewqi.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2qxfielyq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2ypnuwthw.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2zeyxehjc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgukjfqe.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2haoxdoek.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gt2snnyzteb.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gt2cgoyrhia.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gt2vzpvkuht.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2knrxzuwp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gt2wmjfvbkz.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2lhtqgtht.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gt2zvphyyke.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2yhjbxzcq.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gt2ftrrdopn.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gt2zhybkhcp.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2bwtkhkxq.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2bskgbgvw.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gt2luslikzk.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2dtubhgzu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gt2nkdbdsml.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2snpwvlpf.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2hiljnrvo.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2xedeefyz.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gt2unsscjea.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2fnjwnrws.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gt2cxlxsdbr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jxsruaxl.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2phxmkopt.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gt2cmufopbx.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gt2axtwwuuq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ytbrknxt.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gt2rfcpmsmj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kzlqgtmk.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gt2noulylwx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2czyljskk.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2rqbueuxt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2gburypit.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gt2zclzjuuy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gt2awxgbgwg.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dygkdqwm.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2hmdkvrch.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gt2rgtsabqm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gt2wyqwpaas.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2edfzjoqv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gt2glnlhbes.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2kmfdxavl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gt2kjubxugw.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gt2kgwfmezu.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gt2kunpeowe.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtcydtym.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gt2uikjucjx.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2fotslahg.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccjqausj.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gt2garomvnd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gt2fhxaxlhv.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2wdtkosgh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2ksxpqbps.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2peyxltis.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gt2llzxdjqw.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2lifgdzzu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2ctclnqau.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2rzabqfhe.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2rbegssps.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2leqvoifw.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2augleflj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2odlmbhku.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2hnsndgwz.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gt2stpemrcl.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2vwdfncad.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gt2lihuulkh.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gt2xbtrmxcs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpzqpgz.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gt2brehybcv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2yvihnbzv.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gt2bhphxvna.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gt2dievgtcl.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gt2vleoqwei.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gt2ivcwcsja.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2fptgdknv.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2drxcnnhi.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gt2utylhslb.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gt2mbkpspmx.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gt2xbvkqiaf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qifxhhku.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2kltshveb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2mzqsiapq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2oedagkbg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gt2knajtaru.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcyywmdj.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2iexeoqhd.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2feqrutzz.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2buimbjhm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gt2bbccgpdz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2wjsirmqg.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2umbeekpv.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gt2gxzowgya.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gt2neyyoylw.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gt2gmiodomp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gt2hkmecfer.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2jfggbaot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wymphhbi.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2gisqvjsn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gt2yyomijxl.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2lfpiiqgm.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2bunbuumh.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gt2bldweeuf.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2gcwgpstx.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2kaxcgocv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gt2nzbeagpx.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gt2setzfcpf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2zgailiky.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuhenhlo.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2zkytpgmi.html


<!-- 参考信息 -->