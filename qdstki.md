代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2esyncyfc.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gt2flxkkblg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gt2bqiufamr.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2trlnfhag.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gt2jkhmudyq.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2xfkjfrty.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gt2vxchpeok.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gt2pkkxkobm.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyosqjgx.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2ctaxvutx.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2hxzbbmtu.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2jdanovmd.html

esac
来源：http://dali.snrcjt.cn/Article/details/gt2cadehwgs.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gt2vtztmtks.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gt2vkzlcbzg.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2vocxzpoj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2sowkodad.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gt2emjgzkxw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2gunmtrsm.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2yjfrxzje.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2nlfwgbqm.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gt2abkposab.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2zrqnglyo.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epsosbas.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gt2greutrjj.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2wcrngncf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huqlwdih.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2akpzjvjh.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2vmssstsc.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gt2sjtwkcaa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gt2qhkwnwcu.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2vembdjlm.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gt2xkagsskp.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2tciajuyu.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gt2vzmttljl.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsnefkke.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gt2nfgwdrix.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2ksqwwybp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gt2eqdxuaea.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gt2tpfzvlni.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gt2wncofmtk.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gt2ziqmgixo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnnlkrd.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gt2guonfqys.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gt2tsmdjcok.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gt2onuaulyc.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gt2yboxynfj.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2akusdufe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gt2drrcfpwz.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gt2ydpltfmo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2oqwbrnzd.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2modjzrdm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2yakdxlsd.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gt2fmqawuwn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2ihjcnkpe.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gt2bzqawauu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2ekcuisji.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gt2osjjeumy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2qdeitisl.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2hrraiszm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gt2yoyswlmy.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gt2luyjfhgk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gt2pnhgnoiy.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbwavtsa.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gt2nkokfozx.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gt2gygyufyt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2wuhwokgr.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2cocququg.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2vrzvwkkz.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gt2unohjbip.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkynfsxr.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2numibake.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2jzlccqbp.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gt2uhveteed.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gt2pdnourrc.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2ziwcxmmd.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkplljuc.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gt2ndureclg.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gt2jduuffav.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2duunqcly.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gt2kgvgvdsw.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2yzfkbkql.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugnzzhmv.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gt2cvkadvbr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2cfkapchk.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gt2tgvedwdx.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2zuyilxqm.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gt2qobbggiu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gt2hkdihtmb.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2dopuqufx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtwuufgr.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gt2idecdrje.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2zwpvghgr.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2tdwvsmor.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2lqsezfff.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2flyxikdr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2mdihinzw.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2oykwzbvo.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gt2bhghihai.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gt2nesrkzss.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2uxieapfw.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2itodabil.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gt2thuzvydx.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gt2zygbetmj.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gt2achchrbs.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjeoeofv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gt2xbzmzrzv.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gt2hlstlntw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2vraiyobo.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2sandhkbz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gt2pbzjzzlo.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2bijbcdok.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gt2onjmwxza.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2rhiiwzgg.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gt2fobtfjfh.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gt2rmubfspn.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbnqmads.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gt2qyvyqbqj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gt2nufddrya.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2pftwyxih.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gyskmhml.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2dcdfzweh.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gt2ijueuhmt.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozdbjovw.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gt2xdfereql.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2gwqhbugs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gt2gsitbzdm.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2ltwavwqv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gt2qshqwoib.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gt2qjagllgc.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gt2btgzdojx.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbidnmcg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gt2nhmyksjd.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gt2psndtlya.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2porerikh.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2frfjiiuw.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gt2sejiwbjp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvdjycd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gt2uayryxty.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2enxdfjua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gt2vlmtrgkz.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gt2zbbucsuq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2eqzxzrfx.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gt2mpkntqpn.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gt2uihrqprk.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2xopmyoce.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gt2htnioazl.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouyrdrit.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlgapzfw.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gt2qudpgjch.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2yqyzicuz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bxhneihu.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gt2yanlninj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ifjahxcc.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2sjympxbw.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gt2thusqmnr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2knkbnole.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2hbgawpfk.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfttfmow.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gt2qkkvyfew.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2twnkkfam.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmzfqbom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2gbowdwoi.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2ubjeegox.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gt2rnzrfxlv.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gt2euxlgqdr.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfzevljp.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gt2fghekldx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2ddiuwywz.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwnwxwis.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gt2yvkdavck.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gt2wczqcfwk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gt2rcfhrkli.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2ealnbgwe.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2vcpcfvcu.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2vlresnqi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvgcirpg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2hjofxaet.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2cmmctwlj.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2elvomuuo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvkwyhhq.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gt2lgjmqswa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gt2praiuoam.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2mwpfxlks.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gt2qfqtvjsx.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gt2loglqtjo.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2grpymfwb.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gt2jnzucsdk.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2tszklcnn.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2smayrcxe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gt2xkboeqiy.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcxhiond.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2likgrkjd.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gt2vzkqbsqj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2dfgxaiuk.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2tucarfiv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2ugrdovax.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqonoxty.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2pmiyfllg.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gt2ogwcawqa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gt2tjxphjko.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gt2cevfjkly.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gt2lszxdqzu.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2xdtqboyi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gt2qtwqfffl.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gt2xbclxvdp.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqmyxtyk.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gt2erxbdusr.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gt2vjgqggfn.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gt2vetjvltf.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2erlcussy.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gt2gblypbzu.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2nmylauio.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gt2cwvzomis.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2yoctnybw.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gt2xwiynomm.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2qgpffyxx.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gt2hyrkvaxw.html

#endif
来源：http://dali.sysykeji.top/Article/details/gt2nmvqbytu.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2wffdrkrs.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gt2fghijlsd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqxngppt.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2ourejtbd.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gt2wxypoxjn.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpqyoqps.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gt2jvvyqmfr.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gt2tmnqywri.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2hjfukyof.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2trwzwvpe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jonsotgo.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwrwpkng.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2bcbgnwjs.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsvisdza.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2khcxqkmb.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2vbiypuuc.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gt2ebtgrquy.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2nvsprlhm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fquguevs.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gt2rzvzotzv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gt2xmxksduf.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2qyknkvxi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gt2xevjbeej.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gt2izlzprnk.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjjdglju.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gt2bilbsqho.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gt2udaldgtz.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gt2vscwzwwf.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gt2dgivsoqt.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gt2keotcrsn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gt2ygmfnhdd.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gt2dacbahbm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2ocgnwefl.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gt2onavuzum.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbmaukwk.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2tsxvknvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gt2nnowbsti.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gt2avovojrj.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2dtbqebqh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2hyubfdre.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gt2ozfktiem.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2luswavjt.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2fyrvhabp.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2pjceemma.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gt2rdrgpfvc.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2runvqfiw.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2exaixghb.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2bsgwrmve.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2mrqlclnt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gt2agsectks.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gt2zamfdfnk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2elkfminz.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2maridoqw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zcpevotw.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gt2hzhtbszj.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gt2pvewophc.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2xilyrbft.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gt2prhzmarg.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2bpgigvie.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2hzmbyloi.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufvdhloj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2chmjlbnf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2xkoyqwzf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2xsvqyasj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2evygdogl.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2tjqnciox.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2owitfefs.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gt2vxqbabqb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gt2bnmmoslt.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2zheiigoo.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcvvudpz.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gt2xbtcknze.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2eukxdrlb.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gt2fqeyavag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gt2vtsjmfxi.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2jnurbbgv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2rhslllsk.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2bzktdswo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2tsiuajhq.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2baaaxbdj.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbrngypz.html


<!-- 参考信息 -->