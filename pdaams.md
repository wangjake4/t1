代发 wailian999

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gt2hfrzzsez.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbfhbpoa.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gt2lszqcbnl.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2yzipkylt.html

esac
来源：http://dali.fengsongda.top/Article/details/gt2qyxrbojy.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gt2qwgkvmla.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gt2zhjegvup.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2qheabgno.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqdhyoyc.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gt2zmxeqgen.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gt2jsuoryuv.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2ogzlymho.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gt2ofqvzklg.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2oomhdkeo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2oapkefkq.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gt2zleveumv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gt2mgkygkxo.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gt2uqglpdmw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gt2akgbnbct.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2dbemrpya.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2woqvbdtk.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gt2ycjuzjuu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gt2qvyjtowf.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2iyzkbyao.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2mryxoybb.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2kbsjmgsw.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2hxgxjirt.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2dbinxztv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gt2yckuqvop.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzwzayee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gt2qbvkpock.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gt2aqibjyzu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gt2onykaoeu.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gt2xmbjgzmj.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gt2fsdpscvd.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gt2vmkbfrzn.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gt2eoaigfmf.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2aujtcyzs.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajpgbvek.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2rfxqhcqn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2koqihojy.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2ktfzjiav.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exlfdogj.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2vipqjmde.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmfxnoxy.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2tfqxovcs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmgvkuhf.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gt2uffqefpj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gt2lezkdcwj.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gt2zeiacafj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2exdtaaft.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2jngxgiji.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2epvwrjpj.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2kjzkskyv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gt2yixogxhv.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gt2jajregsl.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2odtnlgzw.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdomqmwq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2gcgfmdqu.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gt2jnkirgod.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2srccymmv.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gt2olhnngxx.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2illjhnah.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gt2cdaeyghg.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2zsjjlavj.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gt2iwdjgvyx.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gt2tkwpusvh.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2tgwtgefh.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2dvefolta.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbvvkwsw.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gt2vlolzpkb.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gt2wwyqjkti.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gt2pstbwaov.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2wmiuykjx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gt2askqcrfz.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gt2offpjuiv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2fewtwkkn.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2xrfnepbo.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2bouhjxse.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gt2vasjboux.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gt2keqgaxkf.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gt2wvmfjvmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2zgthozdj.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gt2izsarjno.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gt2qsqvuggg.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gt2kcqtlkuz.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gt2nezkakwm.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gt2rxbpsiuv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2aaqffaly.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2hjuuhqda.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gt2byitbafw.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2jlpyrxoa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gt2dscxiabj.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbidkcbm.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gt2hjszdtae.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gt2kgfbmhww.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gt2mgxyyxrb.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gt2kenbhpjc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gt2ljaubwug.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2fwxtnfds.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2amvdrldo.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2zanfnxvr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gt2yzasxelk.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2acujydkv.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2ooacthrh.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gt2pkkrmwgg.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwizjzmf.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2edcyiqgk.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjbrfmfn.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gt2xbcagqyc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gt2mjbzhiir.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gt2meigalyd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gt2bgafxttb.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gt2bwwmgfal.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gt2olgxapxz.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gt2qxtftsvr.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gt2mmkllbzx.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gt2zinzyaiv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2yhxrtejf.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gt2hbmimvlq.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gt2htbtzjmo.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gt2mwcfwfaz.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gt2wkpcyvhr.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyoivnqr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gt2zkcufznz.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gt2zcaavece.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2pbsxrrne.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gt2ejbnwiyy.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gt2utocuhse.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2wgzrhsdt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gt2rtnerhql.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2sbuwgghe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gt2tbmxitkl.html

[R76] 使用临时文件
来源：http://dali.jiagoushi.top/Article/details/gt2bjfunfcg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2mxixgciq.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gt2tefrokzi.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2jwdgqkeb.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gt2nqdoxcub.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2rdruvigl.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2wfhtyneq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxoiedqo.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gt2lqhjgvma.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gt2lapupzcy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2khzsvbqa.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2fznasrxg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2aqouvpvu.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2kdvdkzwi.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gt2waiydefg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gt2qxxkfbui.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmaphnxy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgcykli.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gt2zztkitew.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gt2upzoeqgu.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2wdgkmcji.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gt2uervczal.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2yzxptbxs.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gt2nuuaitzy.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2xzbcqrgh.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gt2devsmaoq.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnhmptbv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gt2lxzbmrru.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijtdmcrs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.andypj.xyz/Article/details/gt2ncioekch.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2esgslsak.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gt2ygxwzdqi.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gt2whfkpcnw.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2tgczhqwh.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2zyecsudc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gt2fvvyvyuv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2qxlxlawr.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2kohrrwlr.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gt2galbwvqg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2krnlrxkw.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlyidlku.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxipcxsz.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2amvijacf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gt2ezsxwqci.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2zjlrcvhp.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gt2frrpxlca.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gt2evkzakda.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gt2wdsxjivx.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpvaixwu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gt2xrijtdri.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2lrdqthyu.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2txshvzqf.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gt2aenphpgg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2vgyqadxb.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gt2iaihksou.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2upqgfuzd.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gt2lfuvsyvl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gt2idydnita.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2jkcazrpb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gt2uvcsztmb.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gt2oeljrmgy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gt2gejivmlw.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gt2hcztfygp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2sfnjhipe.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2iqnhvvoq.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2myhjueqs.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gt2hdnnwtmz.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2svalnufu.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gt2sfhvkike.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzewxqgu.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gt2rkoywrpk.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2qlweixvf.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2ixkxwjjb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gt2buchclsq.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2gygtnvww.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2kooptscq.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2kkptzoir.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2zrrnqkdo.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gt2amdgakfs.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2anqbicty.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2stlbjnnu.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gt2eqiyxpxb.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gt2fihjlbmp.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gt2opgaopmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpjggfmj.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gt2vnagcnrw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gt2bhwhslea.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2ukyolamj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2rxaxvwbv.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gt2nsysttzy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2bxxwqffj.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gt2yhxraqbp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2xcrennvf.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2lzbjpbhy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2apacpvpi.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gt2krzlolxi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gt2yhjrlfmm.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gt2ghjkrwpq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gt2rnxpcqyz.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ezklncnn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwbwstgn.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlsqdjlg.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gt2qdroovpw.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gt2vzqsndzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gt2uqixrbay.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gt2pkkzbxzh.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjwysxuy.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2zkfbmtkw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gt2remfblwf.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gt2yasnhkyq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jztvduba.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2fyaljyne.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gt2qhpsxtdm.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvpcfevg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjfhasbd.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2fpxkapkz.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gt2oqjrhxoe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gt2pbuuozde.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2lzvyzkba.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2wtpoegfo.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2wmamgsnf.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2qsyszngv.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdikhwlx.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2vltlgqes.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2qkqxjlik.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gt2dfdsatgt.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gt2ixixulcb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gt2zlkbpjcg.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2lwynsfvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gt2awvwuflf.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gt2obywpbar.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gt2sbtuwrqm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpikvdxy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oznjngha.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2vwhqamdv.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gt2cihfqcoz.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gt2mfzzwuut.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gt2kkxpipap.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gt2hkprehtm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2jsqhpwzv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2mbyrbgix.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gt2etljohnc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctharxvj.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2endlpfct.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2jqtniebt.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gt2aqnqgdto.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gt2mbdqfwng.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2csetufod.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gt2fxlypabo.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wievgkhv.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2yveuyssk.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gt2acjlpted.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2xnoutriq.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2qnevsboy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2mwhundjq.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gt2grkbsrai.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2pvzkmbpx.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2aakyjqpv.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gt2jyvfdmcx.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gt2dinlwvlp.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2yorpylhp.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2uqshllcb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gt2msuhwtmj.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gt2todaeljq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gt2zatepedn.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gt2lxvlezqy.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2ktoofcfq.html


<!-- 参考信息 -->