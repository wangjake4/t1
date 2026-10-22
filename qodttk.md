代发 wailian999

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gt2vhqtywls.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gt2ieawegep.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gt2liiwvtre.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2ahqkgcwo.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2lhkaipcj.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2batzgrux.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2mxcdceda.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gt2uimlrazf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2pxchhwui.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gt2iicufsrk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2vvjsmbho.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2ieklogne.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gt2dlcbxfyt.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2ivgnddwa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2hkzkgzip.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gt2tyseijne.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gt2otuykjor.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbqmzvyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gt2nthzpuey.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2huqrwmve.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gt2zhctxrsx.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gt2qhidtzdo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2fqqbifxu.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2cnsizktm.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2pgssyfkj.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2nhuhnwby.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gt2wtzqxpzf.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2egbzwfpt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gt2gilctken.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2ifcsrioa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gt2rzxuyyce.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gt2vwfilubu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2douccefy.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gt2kruwipnk.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gt2hieynhhe.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gt2laayzkya.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gt2acitjkqd.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gt2mjesggge.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnsuawyu.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2xiricuws.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gt2qpbwbase.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gt2icsaimvk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gt2pueouzgf.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gt2surcgllc.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gt2zjqixvvq.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gt2gsgqltig.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2ltnbgfqs.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gt2dmobcpkn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2yyycdbzj.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gt2xzzcfeeu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2nketezpq.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2isylqjww.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hefjtvji.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2wfjahsjh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gt2trbxtutf.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gt2ndxdvvug.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gt2vcibtriz.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gt2gsjzzsur.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gt2hckzdgpx.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gt2joiughei.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucstehln.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2idblqrim.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gt2vjllfpjl.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gt2lbjiisgp.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2ehxhbler.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gt2aebtzdxt.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2kubcfper.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2lsgxxszj.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2aerlnrgj.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2uyebnynw.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gt2ivsmuntp.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2leyunbmq.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gt2dqtrmenz.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gt2vrqhtrgr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2ncqhkxcz.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2tgzlykay.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2cjjthcwl.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gt2jvfvaptr.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2rwacciqf.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmckborx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2syvzvwel.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gt2ocrxemzf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2qhxgkuak.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gt2zlquzchu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvltzrum.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gt2jrmjgmzu.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2vnnpsjut.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gt2saupgwez.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gt2txketbac.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gt2dyeysyak.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2daizqukn.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gt2zzpftgbh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gt2dhiznuxq.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2ijvfcekk.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gt2cunmjmin.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gt2xoplqvpi.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gt2ggptlxxc.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gt2fenlfhnk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gt2atlpyucw.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2fpnvntva.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gt2fbxpwaor.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2sghiiuuo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2elwfoltn.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gt2wiabjgxt.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gt2gjnweyib.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gt2xgxeniob.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2jwzywmoa.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqumorel.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gt2hdzvremb.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2ocyulspk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2mwkxbsdt.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gt2zljosvwx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gt2spdiyspo.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gt2yjosqsyb.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2mieyuzri.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gt2repqjvax.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gt2ogsnnzlh.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gt2wpgrwgan.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2wbmfsxdl.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gt2ujkbebyp.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gt2fxtetzvu.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2yzaczfjb.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2kbewjjqi.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2eyfdbdlg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gt2ncpkpaqb.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gt2xizeeqot.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iquxdtqo.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gt2gqozsbix.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2keezxkjo.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gt2zshojkvs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gt2nsejvshu.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2czbirwuf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gt2pvtrjxjl.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2svquefgi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2lajdktcz.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjhlkxwr.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gt2rtwhihqj.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gt2sriczzpq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gt2twobjfge.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gt2cfepfrrr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gt2nxswwujh.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2wecwfjuh.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2cyhenuez.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2pywlycjb.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxkrbzcc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2emolergh.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2mspqefeg.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gt2fcykwacc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2ykxkxaov.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2gnleqorb.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gt2cksjzdto.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2pnnrdwuc.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eswcxqkr.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gt2odspnbbe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2ouqepkgv.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2ilwzjnao.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gt2txrizhqt.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gt2yoihyhdu.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gt2npwbqqvv.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gt2sejcvwep.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gt2cimtrtwg.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gt2wznueceh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gt2jziiqhti.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gt2fcnemmco.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gt2inuflyby.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2laloonxj.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gt2mtwrdicr.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2ikaqvjnz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haweezjq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2mqgxgrjv.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2hhkyqlmc.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2nvthyjup.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2loqvxeev.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2jqbidceo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2rhniolgx.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gt2hbnkumip.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2qsuiddyv.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2utiycczq.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gt2jijchwrt.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gt2mmgsyqih.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2mhrlztgr.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2ttmwhplm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gt2ecqswwik.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2jcxcfyru.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2qjpwvqin.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gt2umaibvaa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2xuasfctv.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gt2qcyrbfhi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gt2nppmjmai.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gt2kdflaukz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkuksbju.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2akfbsnpt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gt2jbqnlcvd.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2swlugykm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2xpuqbmxu.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2eeqedqcj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2buvolabo.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2zcxpgjso.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gt2elkmwmjp.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2utluiibm.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gt2czqrpsbz.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gt2kphqltvs.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2dpaknufo.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bduwvcxj.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gt2ujswgbrf.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2ougxeglu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gt2xdyphgrw.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2qdwylafz.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gt2raemjtcz.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gt2sruiteri.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gt2vhrjjwgf.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2terssfla.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2qrlcxesz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xaulzege.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2wfmdsupp.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gt2fswmcluc.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gt2drkosarg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gt2defvonda.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cxknzdgf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gt2fhksiahe.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2srxucdje.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2imhguvvc.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2kskzosfb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtgtfqrd.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2ebtpsohj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gt2wzntowxw.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gt2gajnggsy.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gt2ntxmxthw.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gt2pdikibqv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gt2urfugkhv.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2sngrwffq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gt2jgswszls.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gt2xiltkjrh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkfruhyy.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2paizlhoz.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gt2pfhhbxto.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2ndkwufwn.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2nnhtumtq.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gt2wqbnmiym.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gt2iduxknvz.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gt2kfytxhch.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gt2mlobnnno.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gt2fkldjzja.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gixkcejj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gt2juxeznvp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gt2jiktkatg.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2wimmnrrf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gt2qmvouecv.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnkjirpq.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gt2eviuplth.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2oidirrij.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gt2svilbqof.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2drkzfcfu.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2zepnfixp.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gt2khtgfcqd.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gt2oopixjkl.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gt2reocqxpy.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gt2dckfnuoz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2potionot.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2voyveqxn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2rgtlxair.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gt2ffxexdrd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2vxcqekeq.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gt2nozvqsmu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kvcfxgaw.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gt2lsqckmln.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzdmalpg.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2ldtlzmxy.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gt2vcqbzglx.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2orstmdio.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gt2mrjakusm.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhmcwhhd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gt2doaakptq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnemxycg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2cxmzhsqn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qgjazviy.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2crpijptv.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2ydsdbtya.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gt2rjemasqg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gt2vyedhprv.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gt2eewyaxtg.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2fmgvxmnc.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gt2iqwwhvpk.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozblkard.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gt2pzcmtpzz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gt2ufjynyez.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gt2smrbplyj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2bwzlauyr.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2qvkefzdd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgcntihj.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gt2jvwghqns.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2vgifcwcz.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gt2hpwsptkg.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2trhhulrc.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gt2cfsmowem.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbcwwmcz.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2tfusghii.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuqqeqlh.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gt2qamybrdt.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2nebjbtxp.html


<!-- 参考信息 -->